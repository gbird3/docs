<div class="section" id="module-pulumi_azure.managementresource">
<span id="managementresource"></span><h1>managementresource<a class="headerlink" href="#module-pulumi_azure.managementresource" title="Permalink to this headline">¶</a></h1>
<dl class="class">
<dt id="pulumi_azure.managementresource.ManangementLock">
<em class="property">class </em><code class="descclassname">pulumi_azure.managementresource.</code><code class="descname">ManangementLock</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>lock_level=None</em>, <em>name=None</em>, <em>notes=None</em>, <em>scope=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.managementresource.ManangementLock" title="Permalink to this definition">¶</a></dt>
<dd><p>Manages a Management Lock which is scoped to a Subscription, Resource Group or Resource.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<em>pulumi.ResourceOptions</em>) – Options for the resource.</li>
<li><strong>lock_level</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the Level to be used for this Lock. Possible values are <cite>CanNotDelete</cite> and <cite>ReadOnly</cite>. Changing this forces a new resource to be created.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the name of the Management Lock. Changing this forces a new resource to be created.</li>
<li><strong>notes</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies some notes about the lock. Maximum of 512 characters. Changing this forces a new resource to be created.</li>
<li><strong>scope</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the scope at which the Management Lock should be created. Changing this forces a new resource to be created.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_azure.managementresource.ManangementLock.lock_level">
<code class="descname">lock_level</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.managementresource.ManangementLock.lock_level" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the Level to be used for this Lock. Possible values are <cite>CanNotDelete</cite> and <cite>ReadOnly</cite>. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.managementresource.ManangementLock.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.managementresource.ManangementLock.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the name of the Management Lock. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.managementresource.ManangementLock.notes">
<code class="descname">notes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.managementresource.ManangementLock.notes" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies some notes about the lock. Maximum of 512 characters. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.managementresource.ManangementLock.scope">
<code class="descname">scope</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.managementresource.ManangementLock.scope" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the scope at which the Management Lock should be created. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.managementresource.ManangementLock.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.managementresource.ManangementLock.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.managementresource.ManangementLock.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.managementresource.ManangementLock.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
</dd></dl>

</dd></dl>

</div>
