---
title: Module sfn
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../index.html">@pulumi/aws</a> &gt; sfn

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="#Activity">class Activity</a>
* <a href="#StateMachine">class StateMachine</a>
* <a href="#ActivityArgs">interface ActivityArgs</a>
* <a href="#ActivityState">interface ActivityState</a>
* <a href="#StateMachineArgs">interface StateMachineArgs</a>
* <a href="#StateMachineState">interface StateMachineState</a>

<a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts">sfn/activity.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts">sfn/stateMachine.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="Activity">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L21">class <b>Activity</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>extends</span> <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Provides a Step Function Activity resource

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as aws from "@pulumi/aws";

const aws_sfn_activity_sfn_activity = new aws.sfn.Activity("sfn_activity", {
    name: "my-activity",
});
```

<h3 class="pdoc-member-header" id="Activity-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L45"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> Activity(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args?: <a href='#ActivityArgs'>ActivityArgs</a>, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a Activity resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

</div>
<h3 class="pdoc-member-header" id="Activity-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L30">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#ActivityState'>ActivityState</a>, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Activity'>Activity</a></pre>


Get an existing Activity resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

</div>
<h3 class="pdoc-member-header" id="Activity-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

</div>
<h3 class="pdoc-member-header" id="Activity-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

</div>
<h3 class="pdoc-member-header" id="Activity-creationDate">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L37">property <b>creationDate</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>creationDate: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The date the activity was created.

</div>
<h3 class="pdoc-member-header" id="Activity-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>ID</a>&gt;;</pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

</div>
<h3 class="pdoc-member-header" id="Activity-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L41">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>name: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the activity to create.

</div>
<h3 class="pdoc-member-header" id="Activity-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L45">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>tags: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>} | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</pre>

Key-value mapping of resource tags

</div>
<h3 class="pdoc-member-header" id="Activity-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>urn: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#URN'>URN</a>&gt;;</pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

</div>
</div>
<h2 class="pdoc-module-header" id="StateMachine">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L10">class <b>StateMachine</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>extends</span> <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Provides a Step Function State Machine resource

<h3 class="pdoc-member-header" id="StateMachine-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L46"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> StateMachine(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#StateMachineArgs'>StateMachineArgs</a>, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a StateMachine resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

</div>
<h3 class="pdoc-member-header" id="StateMachine-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L19">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#StateMachineState'>StateMachineState</a>, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#StateMachine'>StateMachine</a></pre>


Get an existing StateMachine resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

</div>
<h3 class="pdoc-member-header" id="StateMachine-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

</div>
<h3 class="pdoc-member-header" id="StateMachine-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

</div>
<h3 class="pdoc-member-header" id="StateMachine-creationDate">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L26">property <b>creationDate</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>creationDate: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The date the state machine was created.

</div>
<h3 class="pdoc-member-header" id="StateMachine-definition">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L30">property <b>definition</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>definition: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The Amazon States Language definition of the state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachine-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>ID</a>&gt;;</pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

</div>
<h3 class="pdoc-member-header" id="StateMachine-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L34">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>name: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachine-roleArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L38">property <b>roleArn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>roleArn: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The Amazon Resource Name (ARN) of the IAM role to use for this state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachine-status">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L42">property <b>status</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>status: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The current status of the state machine. Either "ACTIVE" or "DELETING".

</div>
<h3 class="pdoc-member-header" id="StateMachine-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L46">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>tags: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>} | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</pre>

Key-value mapping of resource tags

</div>
<h3 class="pdoc-member-header" id="StateMachine-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>urn: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#URN'>URN</a>&gt;;</pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

</div>
</div>
<h2 class="pdoc-module-header" id="ActivityArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L93">interface <b>ActivityArgs</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

The set of arguments for constructing a Activity resource.

<h3 class="pdoc-member-header" id="ActivityArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L97">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>name?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the activity to create.

</div>
<h3 class="pdoc-member-header" id="ActivityArgs-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L101">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>tags?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</pre>

Key-value mapping of resource tags

</div>
</div>
<h2 class="pdoc-module-header" id="ActivityState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L75">interface <b>ActivityState</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

Input properties used for looking up and filtering Activity resources.

<h3 class="pdoc-member-header" id="ActivityState-creationDate">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L79">property <b>creationDate</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>creationDate?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The date the activity was created.

</div>
<h3 class="pdoc-member-header" id="ActivityState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L83">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>name?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the activity to create.

</div>
<h3 class="pdoc-member-header" id="ActivityState-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/activity.ts#L87">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>tags?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</pre>

Key-value mapping of resource tags

</div>
</div>
<h2 class="pdoc-module-header" id="StateMachineArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L118">interface <b>StateMachineArgs</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

The set of arguments for constructing a StateMachine resource.

<h3 class="pdoc-member-header" id="StateMachineArgs-definition">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L122">property <b>definition</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>definition: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The Amazon States Language definition of the state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachineArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L126">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>name?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachineArgs-roleArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L130">property <b>roleArn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>roleArn: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The Amazon Resource Name (ARN) of the IAM role to use for this state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachineArgs-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L134">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>tags?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</pre>

Key-value mapping of resource tags

</div>
</div>
<h2 class="pdoc-module-header" id="StateMachineState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L88">interface <b>StateMachineState</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

Input properties used for looking up and filtering StateMachine resources.

<h3 class="pdoc-member-header" id="StateMachineState-creationDate">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L92">property <b>creationDate</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>creationDate?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The date the state machine was created.

</div>
<h3 class="pdoc-member-header" id="StateMachineState-definition">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L96">property <b>definition</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>definition?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The Amazon States Language definition of the state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachineState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L100">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>name?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The name of the state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachineState-roleArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L104">property <b>roleArn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>roleArn?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The Amazon Resource Name (ARN) of the IAM role to use for this state machine.

</div>
<h3 class="pdoc-member-header" id="StateMachineState-status">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L108">property <b>status</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>status?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The current status of the state machine. Either "ACTIVE" or "DELETING".

</div>
<h3 class="pdoc-member-header" id="StateMachineState-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/sfn/stateMachine.ts#L112">property <b>tags</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>tags?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</pre>

Key-value mapping of resource tags

</div>
</div>
