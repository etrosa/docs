
---
title: "SnatEntry"
block_external_search_index: true
---



Provides a snat resource.

> This content is derived from https://github.com/terraform-providers/terraform-provider-alicloud/blob/master/website/docs/r/snat.html.markdown.



## Create a SnatEntry Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/vpc/#SnatEntry">SnatEntry</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/vpc/#SnatEntryArgs">SnatEntryArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">SnatEntry</span><span class="p">(resource_name, opts=None, </span>snat_entry_name=None<span class="p">, </span>snat_ip=None<span class="p">, </span>snat_table_id=None<span class="p">, </span>source_cidr=None<span class="p">, </span>source_vswitch_id=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewSnatEntry<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/vpc?tab=doc#SnatEntryArgs">SnatEntryArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/vpc?tab=doc#SnatEntry">SnatEntry</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Vpc.SnatEntry.html">SnatEntry</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Vpc.SnatEntryArgs.html">SnatEntryArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>snat_<wbr>entry_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>snat_<wbr>ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>snat_<wbr>table_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source_<wbr>vswitch_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## SnatEntry Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Snat<wbr>Entry<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the snat entry on the server.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Snat<wbr>Entry<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the snat entry on the server.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>snat<wbr>Entry<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the snat entry on the server.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>snat_<wbr>entry_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The id of the snat entry on the server.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>snat_<wbr>entry_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>snat_<wbr>ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>snat_<wbr>table_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>source_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>source_<wbr>vswitch_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing SnatEntry Resource

Get an existing SnatEntry resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/vpc/#SnatEntryState">SnatEntryState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/vpc/#SnatEntry">SnatEntry</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>snat_entry_id=None<span class="p">, </span>snat_entry_name=None<span class="p">, </span>snat_ip=None<span class="p">, </span>snat_table_id=None<span class="p">, </span>source_cidr=None<span class="p">, </span>source_vswitch_id=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetSnatEntry<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/vpc?tab=doc#SnatEntryState">SnatEntryState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/vpc?tab=doc#SnatEntry">SnatEntry</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Vpc.SnatEntry.html">SnatEntry</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Vpc.SnatEntryState.html">SnatEntryState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Entry<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The id of the snat entry on the server.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Entry<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The id of the snat entry on the server.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>snat<wbr>Entry<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The id of the snat entry on the server.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>snat<wbr>Entry<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>snat<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>snat<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source<wbr>Cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source<wbr>Vswitch<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>snat_<wbr>entry_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The id of the snat entry on the server.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>snat_<wbr>entry_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of snat entry.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>snat_<wbr>ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The SNAT ip address, the ip must along bandwidth package public ip which `alicloud.vpc.NatGateway` argument `bandwidth_packages`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>snat_<wbr>table_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The value can get from `alicloud.vpc.NatGateway` Attributes "snat_table_ids".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source_<wbr>cidr</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The private network segment of Ecs. This parameter and the `source_vswitch_id` parameter are mutually exclusive and cannot appear at the same time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source_<wbr>vswitch_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The vswitch ID.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}











<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-alicloud">https://github.com/pulumi/pulumi-alicloud</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    
</dl>
