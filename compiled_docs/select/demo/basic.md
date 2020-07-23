{"title":"基本使用","meta":{"title":"基本使用","description":"\n<p>简单</p>\n","order":"0"},"codes":{"jsx":"import { Select } from '@alifd/next';\n\nconst Option = Select.Option;\n\nconst onChange = function (value) {\n    console.log(value);\n};\n\nconst onToggleHighlightItem = function (item, type) {\n    console.log(item, type);\n};\n\nconst onFocus = () => {\n  console.log('focus');\n};\n\nconst onBlur = () => {\n  console.log('blur');\n};\n\nReactDOM.render(\n  <Select\n    id=\"basic-demo\"\n    onChange={onChange}\n    onToggleHighlightItem={onToggleHighlightItem}\n    defaultValue=\"jack\"\n    onFocus={onFocus}\n    onBlur={onBlur}\n    aria-label=\"name is\"\n  >\n    <Option value=\"jack\">Jack</Option>\n    <Option value=\"frank\">Frank</Option>\n    <Option value=\"hugo\">Hugo</Option>\n  </Select>,\n  mountNode\n);\n"},"body":"\n\n````jsx\nimport { Select } from '@alifd/next';\n\nconst Option = Select.Option;\n\nconst onChange = function (value) {\n    console.log(value);\n};\n\nconst onToggleHighlightItem = function (item, type) {\n    console.log(item, type);\n};\n\nconst onFocus = () => {\n  console.log('focus');\n};\n\nconst onBlur = () => {\n  console.log('blur');\n};\n\nReactDOM.render(\n  <Select\n    id=\"basic-demo\"\n    onChange={onChange}\n    onToggleHighlightItem={onToggleHighlightItem}\n    defaultValue=\"jack\"\n    onFocus={onFocus}\n    onBlur={onBlur}\n    aria-label=\"name is\"\n  >\n    <Option value=\"jack\">Jack</Option>\n    <Option value=\"frank\">Frank</Option>\n    <Option value=\"hugo\">Hugo</Option>\n  </Select>,\n  mountNode\n);\n````","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar Option = _next.Select.Option;\n\nvar onChange = function onChange(value) {\n  console.log(value);\n};\n\nvar onToggleHighlightItem = function onToggleHighlightItem(item, type) {\n  console.log(item, type);\n};\n\nvar onFocus = function onFocus() {\n  console.log('focus');\n};\n\nvar onBlur = function onBlur() {\n  console.log('blur');\n};\n\nReactDOM.render(React.createElement(\n  _next.Select,\n  {\n    id: 'basic-demo',\n    onChange: onChange,\n    onToggleHighlightItem: onToggleHighlightItem,\n    defaultValue: 'jack',\n    onFocus: onFocus,\n    onBlur: onBlur,\n    'aria-label': 'name is'\n  },\n  React.createElement(\n    Option,\n    { value: 'jack' },\n    'Jack'\n  ),\n  React.createElement(\n    Option,\n    { value: 'frank' },\n    'Frank'\n  ),\n  React.createElement(\n    Option,\n    { value: 'hugo' },\n    'Hugo'\n  )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Select <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> Option <span class=\"token operator\">=</span> Select<span class=\"token punctuation\">.</span>Option<span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">onChange</span> <span class=\"token operator\">=</span> <span class=\"token keyword\">function</span> <span class=\"token punctuation\">(</span><span class=\"token parameter\">value</span><span class=\"token punctuation\">)</span> <span class=\"token punctuation\">{</span>\n    console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span>value<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">onToggleHighlightItem</span> <span class=\"token operator\">=</span> <span class=\"token keyword\">function</span> <span class=\"token punctuation\">(</span><span class=\"token parameter\">item<span class=\"token punctuation\">,</span> type</span><span class=\"token punctuation\">)</span> <span class=\"token punctuation\">{</span>\n    console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span>item<span class=\"token punctuation\">,</span> type<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">onFocus</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n  console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span><span class=\"token string\">'focus'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">onBlur</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n  console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span><span class=\"token string\">'blur'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n  <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Select</span></span>\n    <span class=\"token attr-name\">id</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>basic-demo<span class=\"token punctuation\">\"</span></span>\n    <span class=\"token attr-name\">onChange</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>onChange<span class=\"token punctuation\">}</span></span>\n    <span class=\"token attr-name\">onToggleHighlightItem</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>onToggleHighlightItem<span class=\"token punctuation\">}</span></span>\n    <span class=\"token attr-name\">defaultValue</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>jack<span class=\"token punctuation\">\"</span></span>\n    <span class=\"token attr-name\">onFocus</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>onFocus<span class=\"token punctuation\">}</span></span>\n    <span class=\"token attr-name\">onBlur</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>onBlur<span class=\"token punctuation\">}</span></span>\n    <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>name is<span class=\"token punctuation\">\"</span></span>\n  <span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Option</span></span> <span class=\"token attr-name\">value</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>jack<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Jack</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Option</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Option</span></span> <span class=\"token attr-name\">value</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>frank<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Frank</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Option</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Option</span></span> <span class=\"token attr-name\">value</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>hugo<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Hugo</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Option</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n  </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Select</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span>\n  mountNode\n<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}