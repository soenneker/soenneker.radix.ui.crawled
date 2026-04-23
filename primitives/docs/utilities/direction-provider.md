<html>
	<head>
		<meta name="color-scheme" content="light dark">
	</head>
	<body>
		<pre style="word-wrap: break-word; white-space: pre-wrap;"># Direction Provider  Wraps your app to provide global reading direction.  ## Features  - Enables all primitives to inherit global reading direction.  ## [Installation](#installation)  Install the component from your command line.  ```bash npm install @radix-ui/react-direction ```  ## [Anatomy](#anatomy)  Import the component.  ```jsx import { Direction } from "radix-ui";  export default () =&gt; &lt;Direction.Provider /&gt;; ```  ## [API Reference](#api-reference)  ### [Provider](#provider)  When creating localized apps that require right-to-left (RTL) reading direction, you need to wrap your application with the `Direction.Provider` component to ensure all of the primitives adjust their behavior based on the `dir` prop.  | Prop  | Type   | Default          | | ----- | ------ | ---------------- | | `dir` | `enum` | No default value |  ## [Example](#example)  Use the direction provider.  ```jsx import { Direction } from "radix-ui";  export default () =&gt; &lt;Direction.Provider dir="rtl"&gt;{/* your app */}&lt;/Direction.Provider&gt;; ```
		</pre>
	</body>
</html>