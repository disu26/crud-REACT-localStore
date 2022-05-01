#### Mejoras realizadas al código ###

![image](https://user-images.githubusercontent.com/80411541/166154171-e12688e6-1ea6-4bb2-b80f-5f37c07641f4.png)

Se editó la barra de búsqueda, para crearla utilizando bootstrap y así se pudo borrar su correspondiente archivo .css

![image](https://user-images.githubusercontent.com/80411541/166154212-a62307a2-95ea-4561-9f3e-3e11788415bc.png)

Antes se podían crear To Dos vacíos, se realizó una validación adicional para que esto no se pudiera y se mostrara un mensaje en caso de intentarlo.

![image](https://user-images.githubusercontent.com/80411541/166154245-a4eca5c4-84f3-4f3a-8e96-39cb1865e2cb.png)

Se presentaba un error al crear dos to dos iguales, ya que este valor era asignado como la llave de estos, este error se arregló haciendo uso de uuidv4, que sirve para crear un identificador único para cada to do.

![image](https://user-images.githubusercontent.com/80411541/166154312-7eb417e0-beee-4e62-bef2-68f93c1e27dd.png)

Se modificaron los íconos de completar y de eliminar utilizando React-Icons, de esta manera se ven más agradables.

![image](https://user-images.githubusercontent.com/80411541/166154338-960a0705-9248-4ab0-ab5a-637caf9114e2.png)

Se modificó el mensaje de to dos completados, utilizando bootstrap y React-Icons, para darle un diseño más amigable.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
