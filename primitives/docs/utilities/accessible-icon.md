<html>
	<head>
		<meta name="color-scheme" content="light dark">
	</head>
	<body>
		<pre style="word-wrap: break-word; white-space: pre-wrap;"># Accessible Icon  Makes icons accessible by adding a label.  ## Features  - Quickly make any icon accessible by wrapping it and providing a meaningful label.  - No visual difference, but announced correctly by screen readers.  ## [Installation](#installation)  Install the component from your command line.  ```bash npm install @radix-ui/react-accessible-icon ```  ## [Anatomy](#anatomy)  Import the component.  ```jsx import { AccessibleIcon } from "radix-ui";  export default () =&gt; &lt;AccessibleIcon.Root /&gt;; ```  ## [API Reference](#api-reference)  ### [Root](#root)  Contains the icon to make accessible.  | Prop     | Type     | Default          | | -------- | -------- | ---------------- | | `label*` | `string` | No default value |  ## [Accessibility](#accessibility)  Most icons or icon systems come with no accessibility built-in. For example, the same visual **cross** icon may in fact mean **"close"** or **"delete"**. This component lets you give meaning to icons used throughout your app.  This is built with [Visually Hidden](/primitives/docs/utilities/visually-hidden).
		</pre>
	</body>
</html>