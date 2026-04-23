<html>
	<head>
		<meta name="color-scheme" content="light dark">
	</head>
	<body>
		<pre style="word-wrap: break-word; white-space: pre-wrap;"># Visually Hidden  Hides content from the screen in an accessible way.  ## Features  - Visually hides content while preserving it for assistive technology.  ## [Installation](#installation)  Install the component from your command line.  ```bash npm install @radix-ui/react-visually-hidden ```  ## [Anatomy](#anatomy)  Import the component.  ```jsx import { VisuallyHidden } from "radix-ui";  export default () =&gt; &lt;VisuallyHidden.Root /&gt;; ```  ## [Basic example](#basic-example)  Use the visually hidden primitive.  ```jsx import { VisuallyHidden } from "radix-ui";  import { GearIcon } from "@radix-ui/react-icons";  export default () =&gt; (   &lt;button&gt;     &lt;GearIcon /&gt;      &lt;VisuallyHidden.Root&gt;Settings&lt;/VisuallyHidden.Root&gt;   &lt;/button&gt; ); ```  ## [API Reference](#api-reference)  ### [Root](#root)  Anything you put inside this component will be hidden from the screen but will be announced by screen readers.  | Prop      | Type      | Default | | --------- | --------- | ------- | | `asChild` | `boolean` | `false` |  ## [Accessibility](#accessibility)  This is useful in certain scenarios as an alternative to traditional labelling with `aria-label` or `aria-labelledby`.
		</pre>
	</body>
</html>