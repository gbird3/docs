<div class="section" id="module-pulumi_aws.codedeploy">
<span id="codedeploy"></span><h1>codedeploy<a class="headerlink" href="#module-pulumi_aws.codedeploy" title="Permalink to this headline">¶</a></h1>
<dl class="class">
<dt id="pulumi_aws.codedeploy.Application">
<em class="property">class </em><code class="descclassname">pulumi_aws.codedeploy.</code><code class="descname">Application</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>compute_platform=None</em>, <em>name=None</em>, <em>unique_id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.Application" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a CodeDeploy application to be used as a basis for deployments</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<em>pulumi.ResourceOptions</em>) – Options for the resource.</li>
<li><strong>compute_platform</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The compute platform can either be <cite>ECS</cite>, <cite>Lambda</cite>, or <cite>Server</cite>. Default is <cite>Server</cite>.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the application.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] unique_id</p>
<dl class="attribute">
<dt id="pulumi_aws.codedeploy.Application.compute_platform">
<code class="descname">compute_platform</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.Application.compute_platform" title="Permalink to this definition">¶</a></dt>
<dd><p>The compute platform can either be <cite>ECS</cite>, <cite>Lambda</cite>, or <cite>Server</cite>. Default is <cite>Server</cite>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.Application.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.Application.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the application.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.codedeploy.Application.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.Application.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.codedeploy.Application.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.Application.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_aws.codedeploy.DeploymentConfig">
<em class="property">class </em><code class="descclassname">pulumi_aws.codedeploy.</code><code class="descname">DeploymentConfig</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>compute_platform=None</em>, <em>deployment_config_name=None</em>, <em>minimum_healthy_hosts=None</em>, <em>traffic_routing_config=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentConfig" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a CodeDeploy deployment config for an application</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<em>pulumi.ResourceOptions</em>) – Options for the resource.</li>
<li><strong>compute_platform</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The compute platform can be <cite>Server</cite>, <cite>Lambda</cite>, or <cite>ECS</cite>. Default is <cite>Server</cite>.</li>
<li><strong>deployment_config_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the deployment config.</li>
<li><strong>minimum_healthy_hosts</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A minimum_healthy_hosts block. Minimum Healthy Hosts are documented below.</li>
<li><strong>traffic_routing_config</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A traffic_routing_config block. Traffic Routing Config is documented below.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentConfig.compute_platform">
<code class="descname">compute_platform</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentConfig.compute_platform" title="Permalink to this definition">¶</a></dt>
<dd><p>The compute platform can be <cite>Server</cite>, <cite>Lambda</cite>, or <cite>ECS</cite>. Default is <cite>Server</cite>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentConfig.deployment_config_id">
<code class="descname">deployment_config_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentConfig.deployment_config_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The AWS Assigned deployment config id</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentConfig.deployment_config_name">
<code class="descname">deployment_config_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentConfig.deployment_config_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the deployment config.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentConfig.minimum_healthy_hosts">
<code class="descname">minimum_healthy_hosts</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentConfig.minimum_healthy_hosts" title="Permalink to this definition">¶</a></dt>
<dd><p>A minimum_healthy_hosts block. Minimum Healthy Hosts are documented below.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentConfig.traffic_routing_config">
<code class="descname">traffic_routing_config</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentConfig.traffic_routing_config" title="Permalink to this definition">¶</a></dt>
<dd><p>A traffic_routing_config block. Traffic Routing Config is documented below.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.codedeploy.DeploymentConfig.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentConfig.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.codedeploy.DeploymentConfig.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentConfig.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_aws.codedeploy.DeploymentGroup">
<em class="property">class </em><code class="descclassname">pulumi_aws.codedeploy.</code><code class="descname">DeploymentGroup</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>alarm_configuration=None</em>, <em>app_name=None</em>, <em>auto_rollback_configuration=None</em>, <em>autoscaling_groups=None</em>, <em>blue_green_deployment_config=None</em>, <em>deployment_config_name=None</em>, <em>deployment_group_name=None</em>, <em>deployment_style=None</em>, <em>ec2_tag_filters=None</em>, <em>ec2_tag_sets=None</em>, <em>ecs_service=None</em>, <em>load_balancer_info=None</em>, <em>on_premises_instance_tag_filters=None</em>, <em>service_role_arn=None</em>, <em>trigger_configurations=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a CodeDeploy Deployment Group for a CodeDeploy Application</p>
<p>&gt; <strong>NOTE on blue/green deployments:</strong> When using <cite>green_fleet_provisioning_option</cite> with the <cite>COPY_AUTO_SCALING_GROUP</cite> action, CodeDeploy will create a new ASG with a different name. This ASG is _not_ managed by terraform and will conflict with existing configuration and state. You may want to use a different approach to managing deployments that involve multiple ASG, such as <cite>DISCOVER_EXISTING</cite> with separate blue and green ASG.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<em>pulumi.ResourceOptions</em>) – Options for the resource.</li>
<li><strong>alarm_configuration</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration block of alarms associated with the deployment group (documented below).</li>
<li><strong>app_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the application.</li>
<li><strong>auto_rollback_configuration</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration block of the automatic rollback configuration associated with the deployment group (documented below).</li>
<li><strong>autoscaling_groups</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Autoscaling groups associated with the deployment group.</li>
<li><strong>blue_green_deployment_config</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration block of the blue/green deployment options for a deployment group (documented below).</li>
<li><strong>deployment_config_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the group’s deployment config. The default is “CodeDeployDefault.OneAtATime”.</li>
<li><strong>deployment_group_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the deployment group.</li>
<li><strong>deployment_style</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration block of the type of deployment, either in-place or blue/green, you want to run and whether to route deployment traffic behind a load balancer (documented below).</li>
<li><strong>ec2_tag_filters</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Tag filters associated with the deployment group. See the AWS docs for details.</li>
<li><strong>ec2_tag_sets</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Configuration block(s) of Tag filters associated with the deployment group, which are also referred to as tag groups (documented below). See the AWS docs for details.</li>
<li><strong>ecs_service</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration block(s) of the ECS services for a deployment group (documented below).</li>
<li><strong>load_balancer_info</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Single configuration block of the load balancer to use in a blue/green deployment (documented below).</li>
<li><strong>on_premises_instance_tag_filters</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – On premise tag filters associated with the group. See the AWS docs for details.</li>
<li><strong>service_role_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The service role ARN that allows deployments.</li>
<li><strong>trigger_configurations</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Configuration block(s) of the triggers for the deployment group (documented below).</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.alarm_configuration">
<code class="descname">alarm_configuration</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.alarm_configuration" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration block of alarms associated with the deployment group (documented below).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.app_name">
<code class="descname">app_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.app_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the application.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.auto_rollback_configuration">
<code class="descname">auto_rollback_configuration</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.auto_rollback_configuration" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration block of the automatic rollback configuration associated with the deployment group (documented below).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.autoscaling_groups">
<code class="descname">autoscaling_groups</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.autoscaling_groups" title="Permalink to this definition">¶</a></dt>
<dd><p>Autoscaling groups associated with the deployment group.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.blue_green_deployment_config">
<code class="descname">blue_green_deployment_config</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.blue_green_deployment_config" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration block of the blue/green deployment options for a deployment group (documented below).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.deployment_config_name">
<code class="descname">deployment_config_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.deployment_config_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the group’s deployment config. The default is “CodeDeployDefault.OneAtATime”.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.deployment_group_name">
<code class="descname">deployment_group_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.deployment_group_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the deployment group.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.deployment_style">
<code class="descname">deployment_style</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.deployment_style" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration block of the type of deployment, either in-place or blue/green, you want to run and whether to route deployment traffic behind a load balancer (documented below).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.ec2_tag_filters">
<code class="descname">ec2_tag_filters</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.ec2_tag_filters" title="Permalink to this definition">¶</a></dt>
<dd><p>Tag filters associated with the deployment group. See the AWS docs for details.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.ec2_tag_sets">
<code class="descname">ec2_tag_sets</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.ec2_tag_sets" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration block(s) of Tag filters associated with the deployment group, which are also referred to as tag groups (documented below). See the AWS docs for details.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.ecs_service">
<code class="descname">ecs_service</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.ecs_service" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration block(s) of the ECS services for a deployment group (documented below).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.load_balancer_info">
<code class="descname">load_balancer_info</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.load_balancer_info" title="Permalink to this definition">¶</a></dt>
<dd><p>Single configuration block of the load balancer to use in a blue/green deployment (documented below).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.on_premises_instance_tag_filters">
<code class="descname">on_premises_instance_tag_filters</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.on_premises_instance_tag_filters" title="Permalink to this definition">¶</a></dt>
<dd><p>On premise tag filters associated with the group. See the AWS docs for details.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.service_role_arn">
<code class="descname">service_role_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.service_role_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The service role ARN that allows deployments.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.trigger_configurations">
<code class="descname">trigger_configurations</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.trigger_configurations" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration block(s) of the triggers for the deployment group (documented below).</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.codedeploy.DeploymentGroup.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.codedeploy.DeploymentGroup.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
</dd></dl>

</dd></dl>

</div>
