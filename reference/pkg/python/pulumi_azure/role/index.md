<div class="section" id="module-pulumi_azure.role">
<span id="role"></span><h1>role<a class="headerlink" href="#module-pulumi_azure.role" title="Permalink to this headline">¶</a></h1>
<dl class="class">
<dt id="pulumi_azure.role.Assignment">
<em class="property">class </em><code class="descclassname">pulumi_azure.role.</code><code class="descname">Assignment</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>name=None</em>, <em>principal_id=None</em>, <em>role_definition_id=None</em>, <em>role_definition_name=None</em>, <em>scope=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.Assignment" title="Permalink to this definition">¶</a></dt>
<dd><p>Assigns a given Principal (User or Application) to a given Role.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<em>pulumi.ResourceOptions</em>) – Options for the resource.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A unique UUID/GUID for this Role Assignment - one will be generated if not specified. Changing this forces a new resource to be created.</li>
<li><strong>principal_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Principal (User or Application) to assign the Role Definition to. Changing this forces a new resource to be created.</li>
<li><strong>role_definition_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Scoped-ID of the Role Definition. Changing this forces a new resource to be created. Conflicts with <cite>role_definition_name</cite>.</li>
<li><strong>role_definition_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of a built-in Role. Changing this forces a new resource to be created. Conflicts with <cite>role_definition_id</cite>.</li>
<li><strong>scope</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The scope at which the Role Assignment applies too, such as <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333</cite>, <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup</cite>, or <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup/providers/Microsoft.Compute/virtualMachines/myVM</cite>. Changing this forces a new resource to be created.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_azure.role.Assignment.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Assignment.name" title="Permalink to this definition">¶</a></dt>
<dd><p>A unique UUID/GUID for this Role Assignment - one will be generated if not specified. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Assignment.principal_id">
<code class="descname">principal_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Assignment.principal_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the Principal (User or Application) to assign the Role Definition to. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Assignment.role_definition_id">
<code class="descname">role_definition_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Assignment.role_definition_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The Scoped-ID of the Role Definition. Changing this forces a new resource to be created. Conflicts with <cite>role_definition_name</cite>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Assignment.role_definition_name">
<code class="descname">role_definition_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Assignment.role_definition_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of a built-in Role. Changing this forces a new resource to be created. Conflicts with <cite>role_definition_id</cite>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Assignment.scope">
<code class="descname">scope</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Assignment.scope" title="Permalink to this definition">¶</a></dt>
<dd><p>The scope at which the Role Assignment applies too, such as <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333</cite>, <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup</cite>, or <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup/providers/Microsoft.Compute/virtualMachines/myVM</cite>. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.role.Assignment.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.Assignment.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.role.Assignment.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.Assignment.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_azure.role.Definition">
<em class="property">class </em><code class="descclassname">pulumi_azure.role.</code><code class="descname">Definition</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>assignable_scopes=None</em>, <em>description=None</em>, <em>name=None</em>, <em>permissions=None</em>, <em>role_definition_id=None</em>, <em>scope=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.Definition" title="Permalink to this definition">¶</a></dt>
<dd><p>Manages a custom Role Definition, used to assign Roles to Users/Principals. See [‘Understand role definitions’](<a class="reference external" href="https://docs.microsoft.com/en-us/azure/role-based-access-control/role-definitions">https://docs.microsoft.com/en-us/azure/role-based-access-control/role-definitions</a>) in the Azure documentation for more details.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<em>pulumi.ResourceOptions</em>) – Options for the resource.</li>
<li><strong>assignable_scopes</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – One or more assignable scopes for this Role Definition, such as <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333</cite>, <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup</cite>, or <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup/providers/Microsoft.Compute/virtualMachines/myVM</cite>.</li>
<li><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A description of the Role Definition.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the Role Definition. Changing this forces a new resource to be created.</li>
<li><strong>permissions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A <cite>permissions</cite> block as defined below.</li>
<li><strong>role_definition_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A unique UUID/GUID which identifies this role - one will be generated if not specified. Changing this forces a new resource to be created.</li>
<li><strong>scope</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The scope at which the Role Definition applies too, such as <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333</cite>, <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup</cite>, or <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup/providers/Microsoft.Compute/virtualMachines/myVM</cite>. Changing this forces a new resource to be created.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_azure.role.Definition.assignable_scopes">
<code class="descname">assignable_scopes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Definition.assignable_scopes" title="Permalink to this definition">¶</a></dt>
<dd><p>One or more assignable scopes for this Role Definition, such as <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333</cite>, <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup</cite>, or <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup/providers/Microsoft.Compute/virtualMachines/myVM</cite>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Definition.description">
<code class="descname">description</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Definition.description" title="Permalink to this definition">¶</a></dt>
<dd><p>A description of the Role Definition.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Definition.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Definition.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the Role Definition. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Definition.permissions">
<code class="descname">permissions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Definition.permissions" title="Permalink to this definition">¶</a></dt>
<dd><p>A <cite>permissions</cite> block as defined below.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Definition.role_definition_id">
<code class="descname">role_definition_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Definition.role_definition_id" title="Permalink to this definition">¶</a></dt>
<dd><p>A unique UUID/GUID which identifies this role - one will be generated if not specified. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.Definition.scope">
<code class="descname">scope</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.Definition.scope" title="Permalink to this definition">¶</a></dt>
<dd><p>The scope at which the Role Definition applies too, such as <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333</cite>, <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup</cite>, or <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup/providers/Microsoft.Compute/virtualMachines/myVM</cite>. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.role.Definition.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.Definition.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.role.Definition.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.Definition.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_azure.role.GetBuiltinRoleDefinitionResult">
<em class="property">class </em><code class="descclassname">pulumi_azure.role.</code><code class="descname">GetBuiltinRoleDefinitionResult</code><span class="sig-paren">(</span><em>assignable_scopes=None</em>, <em>description=None</em>, <em>permissions=None</em>, <em>type=None</em>, <em>id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.GetBuiltinRoleDefinitionResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getBuiltinRoleDefinition.</p>
<dl class="attribute">
<dt id="pulumi_azure.role.GetBuiltinRoleDefinitionResult.assignable_scopes">
<code class="descname">assignable_scopes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetBuiltinRoleDefinitionResult.assignable_scopes" title="Permalink to this definition">¶</a></dt>
<dd><p>One or more assignable scopes for this Role Definition, such as <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333</cite>, <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup</cite>, or <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup/providers/Microsoft.Compute/virtualMachines/myVM</cite>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.GetBuiltinRoleDefinitionResult.description">
<code class="descname">description</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetBuiltinRoleDefinitionResult.description" title="Permalink to this definition">¶</a></dt>
<dd><p>the Description of the built-in Role.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.GetBuiltinRoleDefinitionResult.permissions">
<code class="descname">permissions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetBuiltinRoleDefinitionResult.permissions" title="Permalink to this definition">¶</a></dt>
<dd><p>a <cite>permissions</cite> block as documented below.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.GetBuiltinRoleDefinitionResult.type">
<code class="descname">type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetBuiltinRoleDefinitionResult.type" title="Permalink to this definition">¶</a></dt>
<dd><p>the Type of the Role.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.GetBuiltinRoleDefinitionResult.id">
<code class="descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetBuiltinRoleDefinitionResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_azure.role.GetRoleDefinitionResult">
<em class="property">class </em><code class="descclassname">pulumi_azure.role.</code><code class="descname">GetRoleDefinitionResult</code><span class="sig-paren">(</span><em>assignable_scopes=None</em>, <em>description=None</em>, <em>name=None</em>, <em>permissions=None</em>, <em>type=None</em>, <em>id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.GetRoleDefinitionResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getRoleDefinition.</p>
<dl class="attribute">
<dt id="pulumi_azure.role.GetRoleDefinitionResult.assignable_scopes">
<code class="descname">assignable_scopes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetRoleDefinitionResult.assignable_scopes" title="Permalink to this definition">¶</a></dt>
<dd><p>One or more assignable scopes for this Role Definition, such as <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333</cite>, <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup</cite>, or <cite>/subscriptions/0b1f6471-1bf0-4dda-aec3-111122223333/resourceGroups/myGroup/providers/Microsoft.Compute/virtualMachines/myVM</cite>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.GetRoleDefinitionResult.description">
<code class="descname">description</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetRoleDefinitionResult.description" title="Permalink to this definition">¶</a></dt>
<dd><p>the Description of the built-in Role.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.GetRoleDefinitionResult.permissions">
<code class="descname">permissions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetRoleDefinitionResult.permissions" title="Permalink to this definition">¶</a></dt>
<dd><p>a <cite>permissions</cite> block as documented below.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.GetRoleDefinitionResult.type">
<code class="descname">type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetRoleDefinitionResult.type" title="Permalink to this definition">¶</a></dt>
<dd><p>the Type of the Role.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.role.GetRoleDefinitionResult.id">
<code class="descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.role.GetRoleDefinitionResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="function">
<dt id="pulumi_azure.role.get_builtin_role_definition">
<code class="descclassname">pulumi_azure.role.</code><code class="descname">get_builtin_role_definition</code><span class="sig-paren">(</span><em>name=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.get_builtin_role_definition" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about a built-in Role Definition. To access information about a custom Role Definition, please see the <cite>azurerm_role_definition</cite> data source instead.</p>
</dd></dl>

<dl class="function">
<dt id="pulumi_azure.role.get_role_definition">
<code class="descclassname">pulumi_azure.role.</code><code class="descname">get_role_definition</code><span class="sig-paren">(</span><em>role_definition_id=None</em>, <em>scope=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.role.get_role_definition" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing Custom Role Definition. To access information about a built-in Role Definition, please see the <cite>azurerm_builtin_role_definition</cite> data source instead.</p>
</dd></dl>

</div>
