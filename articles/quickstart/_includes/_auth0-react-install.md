<!-- markdownlint-disable MD041 MD002 -->

## Install the Auth0 React SDK

Run the following command within your project directory to install the Auth0 React SDK:

<% if (typeof v2 === 'undefined' || v2 === false) { %>
```bash
npm install @auth0/auth0-react
```
<% } else { %>
```bash
npm install @auth0/auth0-react@beta
```
<% } %>

The SDK exposes methods and variables that help you integrate Auth0 with your React application idiomatically using [React Hooks](https://reactjs.org/docs/hooks-overview.html) or [Higher-Order Components](https://reactjs.org/docs/higher-order-components.html).