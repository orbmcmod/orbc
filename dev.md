## build mod
`./gradlew genSources`
`./gradlew build`

## server on codespace
`npm i ngrok --save-dev`
`./gradlew runServer`
`./node_modules/.bin/ngrok tcp 25565`