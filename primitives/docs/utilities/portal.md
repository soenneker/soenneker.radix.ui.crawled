<html>
	<head>
		<meta name="color-scheme" content="light dark">
	</head>
	<body>
		<pre style="word-wrap: break-word; white-space: pre-wrap;"># Portal  Renders a React subtree in a different part of the DOM.  ## Features  - Render any React subtree outside of your App.  - Appends to \`document.body\` by default but can be customized to use a different container.  ## [Installation](#installation)  Install the component from your command line.  ```bash npm install @radix-ui/react-portal ```  ## [Anatomy](#anatomy)  Import the component.  ```jsx import { Portal } from "radix-ui";  export default () =&gt; &lt;Portal.Root /&gt;; ```  ## [Basic example](#basic-example)  Use the portal primitive.  ```jsx import { Portal } from "radix-ui";  export default () =&gt; &lt;Portal.Root&gt;Content&lt;/Portal.Root&gt;; ```  ## [API Reference](#api-reference)  ### [Root](#root)  Anything you put inside this component will be rendered in a separate `&lt;div&gt;` element. By default, this element will be appended to `document.body` but you can choose a different container by using the `container` prop.  | Prop        | Type          | Default          | | ----------- | ------------- | ---------------- | | `asChild`   | `boolean`     | `false`          | | `container` | `HTMLElement` | No default value |
		</pre>
	</body>
</html>