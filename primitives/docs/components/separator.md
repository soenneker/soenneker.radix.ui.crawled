<html>
	<head>
		<meta name="color-scheme" content="light dark">
	</head>
	<body>
		<pre style="word-wrap: break-word; white-space: pre-wrap;"># Separator  Visually or semantically separates content.  ## Features  - Supports horizontal and vertical orientations.  ## [Installation](#installation)  Install the component from your command line.  ```bash npm install @radix-ui/react-separator ```  ## [Anatomy](#anatomy)  Import all parts and piece them together.  ```jsx import { Separator } from "radix-ui";  export default () =&gt; &lt;Separator.Root /&gt;; ```  ## [API Reference](#api-reference)  ### [Root](#root)  The separator.  | Prop          | Type      | Default          | | ------------- | --------- | ---------------- | | `asChild`     | `boolean` | `false`          | | `orientation` | `enum`    | `"horizontal"`   | | `decorative`  | `boolean` | No default value |  | Data attribute       | Values                       | | -------------------- | ---------------------------- | | `[data-orientation]` | `"vertical" \| "horizontal"` |  ## [Accessibility](#accessibility)  Adheres to the [`separator` role requirements](https://www.w3.org/TR/wai-aria-1.2/#separator).
		</pre>
	</body>
</html>