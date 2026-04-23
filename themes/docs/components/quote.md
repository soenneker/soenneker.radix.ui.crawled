<html>
	<head>
		<meta name="color-scheme" content="light dark">
	</head>
	<body>
		<pre style="word-wrap: break-word; white-space: pre-wrap;"># Quote  Short inline quotation.  ```jsx &lt;Text&gt;   His famous quote, &lt;Quote&gt;Styles come and go. Good design is a language, not a style&lt;/Quote&gt;,   elegantly summs up Massimo’s philosophy of design. &lt;/Text&gt; ```  ## [API Reference](#api-reference)  This component is based on the `q` element and supports [common margin props](/themes/docs/overview/layout#margin-props).  | Prop       | Type                                                      | Default          | | ---------- | --------------------------------------------------------- | ---------------- | | `asChild`  | `boolean`                                                 | No default value | | `truncate` | `boolean`                                                 | No default value | | `wrap`     | `Responsive&lt;"wrap" \| "nowrap" \| "pretty" \| "balance"&gt;` | No default value |  ## [Examples](#examples)  ### [Truncate](#truncate)  Use the `truncate` prop to truncate text with an ellipsis when it overflows its container.  ```jsx &lt;Flex maxWidth="300px"&gt;   &lt;Quote truncate&gt;     The goal of typography is to relate font size, line height, and line width in a proportional way     that maximizes beauty and makes reading easier and more pleasant.   &lt;/Quote&gt; &lt;/Flex&gt; ```
		</pre>
	</body>
</html>