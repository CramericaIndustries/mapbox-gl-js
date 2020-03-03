1) git clone --branch v1.8.1 https://github.com/mapbox/mapbox-gl-js.git
2) cd mapbox-gl-js
3) npm install

NOTE) if the installation fails on windows, open a new terminal as adminstrator and run
`npm install --global windows-build-tools`

4) npm i yarn
5) to build the js file 'dist/mapbox-gl.js'
yarn run build-prod-min
6) to build the css file 'dist/mapbox-gl.css'
yarn run build-css
