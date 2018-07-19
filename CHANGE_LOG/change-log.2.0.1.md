# Change Log
## Commit Range: v2.0.0..v2.0.1


* __Change logs for release 2.0.1__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 23 Feb 2018 15:33:34 -0500
    [0fbe7a41a82b30de0e0dab188e94330edeeb33eb](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/0fbe7a41a82b30de0e0dab188e94330edeeb33eb) 
    

* __TAPI RI updates for tapi-connectivity@2018-02-16.swagger__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Thu, 22 Feb 2018 14:48:52 -0500
    [14ba55763a4ee4088c7d2baac6821e7775bc5a13](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/14ba55763a4ee4088c7d2baac6821e7775bc5a13) 
    

* __Manually fixed the swagger files to properly handle yang augmentations__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Thu, 22 Feb 2018 13:24:37 -0500
    [458b60516103fbcd1d340f75e09e3ba7ae628713](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/458b60516103fbcd1d340f75e09e3ba7ae628713) 
    

* __Renamed the yang files as per the rfc-draft 6087bis guidelines__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Wed, 21 Feb 2018 11:40:39 -0500
    [b96fc18859e6934b0b7f9be4c2276c2aee0cb7e5](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/b96fc18859e6934b0b7f9be4c2276c2aee0cb7e5) 
    - yang files renamed from &lt;module_name&gt;.yang to
    &lt;module_name&gt;@&lt;revision_date&gt;.yang
    - since *.tree and *.swagger files are autogenerated from yang files, this
    triggers renamess for all tree and swagger files too.

* __Fix: Updated ODU/OTSi/ETH Pac composition to StrictComposite__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 16 Feb 2018 18:35:28 -0500
    [160de368d8135aa9b3e9d45f0c18d4a53881afeb](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/160de368d8135aa9b3e9d45f0c18d4a53881afeb) 
    - the &lt;ExtendedComposite&gt; pattern used in conjunction with
    &lt;Specification&gt; pattern was causing attribute namespace clash as well as 
    cardinality issues in the generated swagger output.

* __Fix: Updated SwitchControl to GlobalClass instead of LocalClass__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 16 Feb 2018 16:07:33 -0500
    [93773bf1c6e7d8f7827a507b336aed67dd03ed87](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/93773bf1c6e7d8f7827a507b336aed67dd03ed87) 
    

* __Updated Notification.ObjectType enum to include additional TAPI2 classes__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 16 Feb 2018 15:51:19 -0500
    [8a8da3d28bc276544722e8380abff07dd321511b](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/8a8da3d28bc276544722e8380abff07dd321511b) 
    - added following enumeration literals: MEG, ME, MEP, MIP, MeasurementJob,
    NodeRuleGroup, InterRuleGroup, Rule, SwitchControl, Switch, Route

* __Added CapacityPac to the NodeEdgePoint__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 16 Feb 2018 15:24:31 -0500
    [2138721c28831cf5c5e1cc0633f98f46714621e5](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/2138721c28831cf5c5e1cc0633f98f46714621e5) 
    - This information is needed to expose NEP capabilities when modeling 
    fixed-mapping cases in a compact/simplified manner without presence of 
    Links/TransitionalLinks attached to the NEP

* __Added the DSR to LayerRateName enumeration__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 16 Feb 2018 14:16:41 -0500
    [eab0713773f137ba4ff86b42981892ceb92d21ec](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/eab0713773f137ba4ff86b42981892ceb92d21ec) 
    - this layerRate is needed to describe variable-rate client ports of simple
    (fixed mapping or single-layer switching) L0 and L1 devices

* __Fixed ConnectivityConstraints &amp; CSEP attributes to be configurable__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 16 Feb 2018 13:20:36 -0500
    [e29e852ddd853e3e4a3a879439c1c8119aa8b735](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/e29e852ddd853e3e4a3a879439c1c8119aa8b735) 
    

* __Renamed Context class/grouping to TapiContext to avoid yang name-clash__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 16 Feb 2018 11:05:03 -0500
    [73f936a263485457dd650c5de03f6b3eab848d11](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/73f936a263485457dd650c5de03f6b3eab848d11) 
    

* __Updated UML/Yang files with version, license, copyright info__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Thu, 15 Feb 2018 14:19:40 -0500
    [f95b227fa82b38b2344440d82ad4a0f38ae4534a](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/f95b227fa82b38b2344440d82ad4a0f38ae4534a) 
    - updated swagger files generated with latest eagle tool fixes to properly
    generate APIs for imported modules in augmenting files

* __Update README.md__

    [Yuta HIGUCHI](mailto:y-higuchi@users.noreply.github.com) - Mon, 12 Feb 2018 17:23:19 -0800
    [f01dbebc39a1e98373a9654b42ed20755ee193cc](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/f01dbebc39a1e98373a9654b42ed20755ee193cc) 
    Update link to SNOWMASS project page

* __Minor Updates__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 9 Feb 2018 15:52:54 -0500
    [6c47e5f5acd146f389df1b533fb512057bf6f98a](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/6c47e5f5acd146f389df1b533fb512057bf6f98a) 
    

* __Updatedyang config file__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Fri, 9 Feb 2018 11:53:26 -0500
    [cf782d5571f3d596151384db69519916fccdd96f](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/cf782d5571f3d596151384db69519916fccdd96f) 
    

* __Initial version of config.json required by the refactored xmi2yang__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Thu, 1 Feb 2018 11:05:10 +0800
    [a0949e562ef65f4815c7694eb86cf3a18a316e6d](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/a0949e562ef65f4815c7694eb86cf3a18a316e6d) 
    

* __Initial commit of TAPI 2.0 RI__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Sat, 27 Jan 2018 02:33:48 -0500
    [ff31c39a3b5b12bd0281ed5ca375c5e93f7646fd](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/ff31c39a3b5b12bd0281ed5ca375c5e93f7646fd) 
    

* __Removing old TAPI 1.0 RI files__

    [karthik-sethuraman](mailto:karthik.sethuraman@necam.com) - Sat, 27 Jan 2018 02:10:56 -0500
    [e79226701f190381dd8247ebcb780111bd852352](https://github.com/OpenNetworkingFoundation/Snowmass-ONFOpenTransport/commit/e79226701f190381dd8247ebcb780111bd852352) 
    

