<!-- Generated with Stardoc: http://skydoc.bazel.build -->

Input file for markdown template test

<a id="example_rule"></a>

## example_rule

<pre>
load("@stardoc//test:testdata/html_tables_template_test/input.bzl", "example_rule")

example_rule(<a href="#example_rule-name">name</a>, <a href="#example_rule-first">first</a>, <a href="#example_rule-second">second</a>)
</pre>

Small example of rule using a markdown template.

### Attributes

<table class="params-table">
<colgroup>
<col class="col-param" />
<col class="col-description" />
</colgroup>
<tbody>
<tr id="example_rule-name">
<td><code>name</code></td>
<td>

<a href="https://bazel.build/concepts/labels#target-names">Name</a>; required

<p>

A unique name for this target.

</p>
</td>
</tr>
<tr id="example_rule-first">
<td><code>first</code></td>
<td>

String; optional

<p>

This is the first attribute

</p>
</td>
</tr>
<tr id="example_rule-second">
<td><code>second</code></td>
<td>

String; optional

</td>
</tr>
</tbody>
</table>


<a id="ExampleProviderInfo"></a>

## ExampleProviderInfo

<pre>
load("@stardoc//test:testdata/html_tables_template_test/input.bzl", "ExampleProviderInfo")

ExampleProviderInfo(<a href="#ExampleProviderInfo-foo">foo</a>, <a href="#ExampleProviderInfo-bar">bar</a>, <a href="#ExampleProviderInfo-baz">baz</a>)
</pre>

Small example of provider using a markdown template.

### Fields

<table class="params-table">
<colgroup>
<col class="col-param" />
<col class="col-description" />
</colgroup>
<tbody>
<tr id="ExampleProviderInfo-foo">
<td><code>foo</code></td>
<td>
<p>

A string representing foo

</p>
</td>
</tr>
<tr id="ExampleProviderInfo-bar">
<td><code>bar</code></td>
<td>
<p>

A string representing bar

</p>
</td>
</tr>
<tr id="ExampleProviderInfo-baz">
<td><code>baz</code></td>
<td>
<p>

A string representing baz

</p>
</td>
</tr>
</tbody>
</table>


<a id="example_function"></a>

## example_function

<pre>
load("@stardoc//test:testdata/html_tables_template_test/input.bzl", "example_function")

example_function(<a href="#example_function-foo">foo</a>, <a href="#example_function-bar">bar</a>)
</pre>

Small example of function using a markdown template.

### Parameters

<table class="params-table">
<colgroup>
<col class="col-param" />
<col class="col-description" />
</colgroup>
<tbody>
<tr id="example_function-foo">
<td><code>foo</code></td>
<td>

required.

<p>

This parameter does foo related things.

</p>
</td>
</tr>
<tr id="example_function-bar">
<td><code>bar</code></td>
<td>

optional.
default is <code>"bar"</code>

<p>

This parameter does bar related things.

</p>
</td>
</tr>
</tbody>
</table>


<a id="example_aspect"></a>

## example_aspect

<pre>
load("@stardoc//test:testdata/html_tables_template_test/input.bzl", "example_aspect")

example_aspect(<a href="#example_aspect-first">first</a>, <a href="#example_aspect-second">second</a>)
</pre>

Small example of aspect using a markdown template.

### Aspect Attributes

<table class="params-table">
<colgroup>
<col class="col-param" />
<col class="col-description" />
</colgroup>
<tbody>
<tr id="example_aspect-deps">
<td><code>deps</code></td>
<td>
String; required.
</td>
</tr>
<tr id="example_aspect-attr_aspect">
<td><code>attr_aspect</code></td>
<td>
String; required.
</td>
</tr>
</tbody>
</table>

### Attributes

<table class="params-table">
<colgroup>
<col class="col-param" />
<col class="col-description" />
</colgroup>
<tbody>
<tr id="example_aspect-first">
<td><code>first</code></td>
<td>

Integer; required

</td>
</tr>
<tr id="example_aspect-second">
<td><code>second</code></td>
<td>

String; optional

<p>

This is the second attribute.

</p>
</td>
</tr>
</tbody>
</table>


