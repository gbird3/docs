---
title: Module servicecatalog
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../index.html">@pulumi/aws</a> &gt; servicecatalog

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="#Portfolio">class Portfolio</a>
* <a href="#PortfolioArgs">interface PortfolioArgs</a>
* <a href="#PortfolioState">interface PortfolioState</a>

<a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts">servicecatalog/portfolio.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="Portfolio">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L23">class <b>Portfolio</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>extends</span> <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Provides a resource to create a Service Catalog Portfolio.

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as aws from "@pulumi/aws";

const aws_servicecatalog_portfolio_portfolio = new aws.servicecatalog.Portfolio("portfolio", {
    description: "List of my organizations apps",
    name: "My App Portfolio",
    providerName: "Brett",
});
```

<h3 class="pdoc-member-header" id="Portfolio-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L53"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> Portfolio(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args?: <a href='#PortfolioArgs'>PortfolioArgs</a>, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a Portfolio resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

</div>
<h3 class="pdoc-member-header" id="Portfolio-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L32">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#PortfolioState'>PortfolioState</a>, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Portfolio'>Portfolio</a></pre>


Get an existing Portfolio resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

</div>
<h3 class="pdoc-member-header" id="Portfolio-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

</div>
<h3 class="pdoc-member-header" id="Portfolio-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

</div>
<h3 class="pdoc-member-header" id="Portfolio-arn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L36">property <b>arn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>arn: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
</div>
<h3 class="pdoc-member-header" id="Portfolio-createdTime">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L37">property <b>createdTime</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>createdTime: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
</div>
<h3 class="pdoc-member-header" id="Portfolio-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L41">property <b>description</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>description: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

Description of the portfolio

</div>
<h3 class="pdoc-member-header" id="Portfolio-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>ID</a>&gt;;</pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

</div>
<h3 class="pdoc-member-header" id="Portfolio-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L45">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>name: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the portfolio.

</div>
<h3 class="pdoc-member-header" id="Portfolio-providerName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L49">property <b>providerName</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>providerName: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</pre>

Name of the person or organization who owns the portfolio.

</div>
<h3 class="pdoc-member-header" id="Portfolio-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L53">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>tags: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>} | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</pre>

Tags to apply to the connection.

</div>
<h3 class="pdoc-member-header" id="Portfolio-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>urn: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#URN'>URN</a>&gt;;</pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

</div>
</div>
<h2 class="pdoc-module-header" id="PortfolioArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L113">interface <b>PortfolioArgs</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

The set of arguments for constructing a Portfolio resource.

<h3 class="pdoc-member-header" id="PortfolioArgs-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L117">property <b>description</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>description?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

Description of the portfolio

</div>
<h3 class="pdoc-member-header" id="PortfolioArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L121">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>name?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the portfolio.

</div>
<h3 class="pdoc-member-header" id="PortfolioArgs-providerName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L125">property <b>providerName</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>providerName?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

Name of the person or organization who owns the portfolio.

</div>
<h3 class="pdoc-member-header" id="PortfolioArgs-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L129">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>tags?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</pre>

Tags to apply to the connection.

</div>
</div>
<h2 class="pdoc-module-header" id="PortfolioState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L89">interface <b>PortfolioState</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

Input properties used for looking up and filtering Portfolio resources.

<h3 class="pdoc-member-header" id="PortfolioState-arn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L90">property <b>arn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>arn?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
</div>
<h3 class="pdoc-member-header" id="PortfolioState-createdTime">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L91">property <b>createdTime</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>createdTime?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
</div>
<h3 class="pdoc-member-header" id="PortfolioState-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L95">property <b>description</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>description?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

Description of the portfolio

</div>
<h3 class="pdoc-member-header" id="PortfolioState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L99">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>name?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the portfolio.

</div>
<h3 class="pdoc-member-header" id="PortfolioState-providerName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L103">property <b>providerName</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>providerName?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

Name of the person or organization who owns the portfolio.

</div>
<h3 class="pdoc-member-header" id="PortfolioState-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/servicecatalog/portfolio.ts#L107">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>tags?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</pre>

Tags to apply to the connection.

</div>
</div>
