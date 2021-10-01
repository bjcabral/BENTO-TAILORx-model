<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

###<center>BENTO-TAILORx Data Model.</center> 
The Bento Core Data Model supports the Bento software framework that has been developed to stand up data sharing platforms for clinical trials and research programs. Modern clinical trials and research programs generate large volumes of complex biomedical data types. To address this complexity, the Bento Core Data model uses a graph structure to model a clinical trial workflow.  Key trial entities are modelled as node types, while the association between nodes are explicitly modelled as relationship types. 
The Bento Core Data Model has been extended to fit the TAILORx clinical data set. The extended model, also called the BENTO_TAILORx data model, comprises of 20 node types and 37 relationship types. Both nodes and relationships store data attributes in the form of properties. These data attributes are listed in the section BENTO_TAILORx Attribute Types. The BENTO_TAILORx graph data model has been implemented in Neo4J, a commercial graph database platform.



Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/bento-tailorx-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="4249pt" height="7026pt"
 viewBox="0.00 0.00 4249.15 7026.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 7022)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-7022 4245.1493,-7022 4245.1493,4 -4,4"/>
<!-- report -->
<g id="node1" class="node">
<title>report</title>
<path fill="none" stroke="#000000" d="M386.1493,-6822C386.1493,-6822 616.1493,-6822 616.1493,-6822 622.1493,-6822 628.1493,-6828 628.1493,-6834 628.1493,-6834 628.1493,-6994 628.1493,-6994 628.1493,-7000 622.1493,-7006 616.1493,-7006 616.1493,-7006 386.1493,-7006 386.1493,-7006 380.1493,-7006 374.1493,-7000 374.1493,-6994 374.1493,-6994 374.1493,-6834 374.1493,-6834 374.1493,-6828 380.1493,-6822 386.1493,-6822"/>
<text text-anchor="middle" x="405.1493" y="-6910.3" font-family="Times,serif" font-size="14.00" fill="#000000">report</text>
<polyline fill="none" stroke="#000000" points="436.1493,-6822 436.1493,-7006 "/>
<text text-anchor="middle" x="446.6493" y="-6910.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="457.1493,-6822 457.1493,-7006 "/>
<text text-anchor="middle" x="532.1493" y="-6990.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="457.1493,-6983 607.1493,-6983 "/>
<text text-anchor="middle" x="532.1493" y="-6967.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_description</text>
<polyline fill="none" stroke="#000000" points="457.1493,-6960 607.1493,-6960 "/>
<text text-anchor="middle" x="532.1493" y="-6944.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_format</text>
<polyline fill="none" stroke="#000000" points="457.1493,-6937 607.1493,-6937 "/>
<text text-anchor="middle" x="532.1493" y="-6921.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_id</text>
<polyline fill="none" stroke="#000000" points="457.1493,-6914 607.1493,-6914 "/>
<text text-anchor="middle" x="532.1493" y="-6898.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_location</text>
<polyline fill="none" stroke="#000000" points="457.1493,-6891 607.1493,-6891 "/>
<text text-anchor="middle" x="532.1493" y="-6875.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_name</text>
<polyline fill="none" stroke="#000000" points="457.1493,-6868 607.1493,-6868 "/>
<text text-anchor="middle" x="532.1493" y="-6852.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_size</text>
<polyline fill="none" stroke="#000000" points="457.1493,-6845 607.1493,-6845 "/>
<text text-anchor="middle" x="532.1493" y="-6829.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_type</text>
<polyline fill="none" stroke="#000000" points="607.1493,-6822 607.1493,-7006 "/>
<text text-anchor="middle" x="617.6493" y="-6910.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M890.6493,-2899.5C890.6493,-2899.5 1313.6493,-2899.5 1313.6493,-2899.5 1319.6493,-2899.5 1325.6493,-2905.5 1325.6493,-2911.5 1325.6493,-2911.5 1325.6493,-3876.5 1325.6493,-3876.5 1325.6493,-3882.5 1319.6493,-3888.5 1313.6493,-3888.5 1313.6493,-3888.5 890.6493,-3888.5 890.6493,-3888.5 884.6493,-3888.5 878.6493,-3882.5 878.6493,-3876.5 878.6493,-3876.5 878.6493,-2911.5 878.6493,-2911.5 878.6493,-2905.5 884.6493,-2899.5 890.6493,-2899.5"/>
<text text-anchor="middle" x="912.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="946.6493,-2899.5 946.6493,-3888.5 "/>
<text text-anchor="middle" x="957.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="967.6493,-2899.5 967.6493,-3888.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3873.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3865.5 1304.6493,-3865.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3850.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_glass</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3842.5 1304.6493,-3842.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3827.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_pigmented_tumor</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3819.5 1304.6493,-3819.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3804.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3796.5 1304.6493,-3796.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3781.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3773.5 1304.6493,-3773.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3758.3" font-family="Times,serif" font-size="14.00" fill="#000000">catalog_reference</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3750.5 1304.6493,-3750.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3735.3" font-family="Times,serif" font-size="14.00" fill="#000000">comment</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3727.5 1304.6493,-3727.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3712.3" font-family="Times,serif" font-size="14.00" fill="#000000">composition</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3704.5 1304.6493,-3704.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3689.3" font-family="Times,serif" font-size="14.00" fill="#000000">current_weight</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3681.5 1304.6493,-3681.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3666.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_sample_collection</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3658.5 1304.6493,-3658.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3643.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_collection</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3635.5 1304.6493,-3635.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3620.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_sample_procurement</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3612.5 1304.6493,-3612.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3597.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_pathologically_confirmed</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3589.5 1304.6493,-3589.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3574.3" font-family="Times,serif" font-size="14.00" fill="#000000">distance_normal_to_tumor</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3566.5 1304.6493,-3566.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3551.3" font-family="Times,serif" font-size="14.00" fill="#000000">distributor_reference</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3543.5 1304.6493,-3543.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3528.3" font-family="Times,serif" font-size="14.00" fill="#000000">growth_rate</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3520.5 1304.6493,-3520.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3505.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_weight</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3497.5 1304.6493,-3497.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3482.3" font-family="Times,serif" font-size="14.00" fill="#000000">intermediate_dimension</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3474.5 1304.6493,-3474.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3459.3" font-family="Times,serif" font-size="14.00" fill="#000000">longest_dimension</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3451.5 1304.6493,-3451.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3436.3" font-family="Times,serif" font-size="14.00" fill="#000000">method_of_sample_procurement</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3428.5 1304.6493,-3428.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3413.3" font-family="Times,serif" font-size="14.00" fill="#000000">necropsy_sample</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3405.5 1304.6493,-3405.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3382.5 1304.6493,-3382.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3367.3" font-family="Times,serif" font-size="14.00" fill="#000000">passage_count</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3359.5 1304.6493,-3359.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3344.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3336.5 1304.6493,-3336.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3321.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3313.5 1304.6493,-3313.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3298.3" font-family="Times,serif" font-size="14.00" fill="#000000">pool</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3290.5 1304.6493,-3290.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3275.3" font-family="Times,serif" font-size="14.00" fill="#000000">preservation_method</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3267.5 1304.6493,-3267.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3252.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3244.5 1304.6493,-3244.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3229.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3221.5 1304.6493,-3221.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3206.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_is_ref</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3198.5 1304.6493,-3198.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3183.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_laterality</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3175.5 1304.6493,-3175.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3160.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3152.5 1304.6493,-3152.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3137.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_id</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3129.5 1304.6493,-3129.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3114.3" font-family="Times,serif" font-size="14.00" fill="#000000">shortest_dimension</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3106.5 1304.6493,-3106.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3091.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_clamping_and_freezing</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3083.5 1304.6493,-3083.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3068.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_excision_and_freezing</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3060.5 1304.6493,-3060.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3045.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_type</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3037.5 1304.6493,-3037.5 "/>
<text text-anchor="middle" x="1136.1493" y="-3022.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_tissue_area</text>
<polyline fill="none" stroke="#000000" points="967.6493,-3014.5 1304.6493,-3014.5 "/>
<text text-anchor="middle" x="1136.1493" y="-2999.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_code</text>
<polyline fill="none" stroke="#000000" points="967.6493,-2991.5 1304.6493,-2991.5 "/>
<text text-anchor="middle" x="1136.1493" y="-2976.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_code_id</text>
<polyline fill="none" stroke="#000000" points="967.6493,-2968.5 1304.6493,-2968.5 "/>
<text text-anchor="middle" x="1136.1493" y="-2953.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_descriptor</text>
<polyline fill="none" stroke="#000000" points="967.6493,-2945.5 1304.6493,-2945.5 "/>
<text text-anchor="middle" x="1136.1493" y="-2930.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="967.6493,-2922.5 1304.6493,-2922.5 "/>
<text text-anchor="middle" x="1136.1493" y="-2907.3" font-family="Times,serif" font-size="14.00" fill="#000000">width_of_tumor</text>
<polyline fill="none" stroke="#000000" points="1304.6493,-2899.5 1304.6493,-3888.5 "/>
<text text-anchor="middle" x="1315.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- report&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>report&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M628.4147,-6897.0159C781.2551,-6873.8598 1024.4515,-6827.2974 1083.1493,-6759 1133.5666,-6700.3373 1102.1493,-6663.3512 1102.1493,-6586 1102.1493,-6586 1102.1493,-6586 1102.1493,-5493 1102.1493,-4948.1701 1102.1493,-4323.7917 1102.1493,-3898.6144"/>
<polygon fill="#000000" stroke="#000000" points="1105.6494,-3898.608 1102.1493,-3888.608 1098.6494,-3898.6081 1105.6494,-3898.608"/>
<text text-anchor="middle" x="1164.6493" y="-6231.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_sample</text>
</g>
<!-- aliquot -->
<g id="node8" class="node">
<title>aliquot</title>
<path fill="none" stroke="#000000" d="M658.1493,-6413.5C658.1493,-6413.5 1062.1493,-6413.5 1062.1493,-6413.5 1068.1493,-6413.5 1074.1493,-6419.5 1074.1493,-6425.5 1074.1493,-6425.5 1074.1493,-6746.5 1074.1493,-6746.5 1074.1493,-6752.5 1068.1493,-6758.5 1062.1493,-6758.5 1062.1493,-6758.5 658.1493,-6758.5 658.1493,-6758.5 652.1493,-6758.5 646.1493,-6752.5 646.1493,-6746.5 646.1493,-6746.5 646.1493,-6425.5 646.1493,-6425.5 646.1493,-6419.5 652.1493,-6413.5 658.1493,-6413.5"/>
<text text-anchor="middle" x="679.1493" y="-6582.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot</text>
<polyline fill="none" stroke="#000000" points="712.1493,-6413.5 712.1493,-6758.5 "/>
<text text-anchor="middle" x="722.6493" y="-6582.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="733.1493,-6413.5 733.1493,-6758.5 "/>
<text text-anchor="middle" x="893.1493" y="-6743.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_concentration</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6735.5 1053.1493,-6735.5 "/>
<text text-anchor="middle" x="893.1493" y="-6720.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_id</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6712.5 1053.1493,-6712.5 "/>
<text text-anchor="middle" x="893.1493" y="-6697.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_is_ref</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6689.5 1053.1493,-6689.5 "/>
<text text-anchor="middle" x="893.1493" y="-6674.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_quantity</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6666.5 1053.1493,-6666.5 "/>
<text text-anchor="middle" x="893.1493" y="-6651.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_volume</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6643.5 1053.1493,-6643.5 "/>
<text text-anchor="middle" x="893.1493" y="-6628.3" font-family="Times,serif" font-size="14.00" fill="#000000">no_matched_normal_low_pass_wgs</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6620.5 1053.1493,-6620.5 "/>
<text text-anchor="middle" x="893.1493" y="-6605.3" font-family="Times,serif" font-size="14.00" fill="#000000">no_matched_normal_targeted_sequencing</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6597.5 1053.1493,-6597.5 "/>
<text text-anchor="middle" x="893.1493" y="-6582.3" font-family="Times,serif" font-size="14.00" fill="#000000">no_matched_normal_wgs</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6574.5 1053.1493,-6574.5 "/>
<text text-anchor="middle" x="893.1493" y="-6559.3" font-family="Times,serif" font-size="14.00" fill="#000000">no_matched_normal_wxs</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6551.5 1053.1493,-6551.5 "/>
<text text-anchor="middle" x="893.1493" y="-6536.3" font-family="Times,serif" font-size="14.00" fill="#000000">pool</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6528.5 1053.1493,-6528.5 "/>
<text text-anchor="middle" x="893.1493" y="-6513.3" font-family="Times,serif" font-size="14.00" fill="#000000">selected_normal_low_pass_wgs</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6505.5 1053.1493,-6505.5 "/>
<text text-anchor="middle" x="893.1493" y="-6490.3" font-family="Times,serif" font-size="14.00" fill="#000000">selected_normal_targeted_sequencing</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6482.5 1053.1493,-6482.5 "/>
<text text-anchor="middle" x="893.1493" y="-6467.3" font-family="Times,serif" font-size="14.00" fill="#000000">selected_normal_wgs</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6459.5 1053.1493,-6459.5 "/>
<text text-anchor="middle" x="893.1493" y="-6444.3" font-family="Times,serif" font-size="14.00" fill="#000000">selected_normal_wxs</text>
<polyline fill="none" stroke="#000000" points="733.1493,-6436.5 1053.1493,-6436.5 "/>
<text text-anchor="middle" x="893.1493" y="-6421.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1053.1493,-6413.5 1053.1493,-6758.5 "/>
<text text-anchor="middle" x="1063.6493" y="-6582.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- report&#45;&gt;aliquot -->
<g id="edge20" class="edge">
<title>report&#45;&gt;aliquot</title>
<path fill="none" stroke="#000000" d="M602.1062,-6821.7608C621.4927,-6804.0485 642.4017,-6784.945 663.631,-6765.5488"/>
<polygon fill="#000000" stroke="#000000" points="666.1297,-6768.0068 671.1515,-6758.6777 661.4081,-6762.8389 666.1297,-6768.0068"/>
<text text-anchor="middle" x="710.1493" y="-6780.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_aliquot</text>
</g>
<!-- analyte -->
<g id="node11" class="node">
<title>analyte</title>
<path fill="none" stroke="#000000" d="M388.1493,-6108.5C388.1493,-6108.5 752.1493,-6108.5 752.1493,-6108.5 758.1493,-6108.5 764.1493,-6114.5 764.1493,-6120.5 764.1493,-6120.5 764.1493,-6349.5 764.1493,-6349.5 764.1493,-6355.5 758.1493,-6361.5 752.1493,-6361.5 752.1493,-6361.5 388.1493,-6361.5 388.1493,-6361.5 382.1493,-6361.5 376.1493,-6355.5 376.1493,-6349.5 376.1493,-6349.5 376.1493,-6120.5 376.1493,-6120.5 376.1493,-6114.5 382.1493,-6108.5 388.1493,-6108.5"/>
<text text-anchor="middle" x="410.6493" y="-6231.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte</text>
<polyline fill="none" stroke="#000000" points="445.1493,-6108.5 445.1493,-6361.5 "/>
<text text-anchor="middle" x="455.6493" y="-6231.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="466.1493,-6108.5 466.1493,-6361.5 "/>
<text text-anchor="middle" x="604.6493" y="-6346.3" font-family="Times,serif" font-size="14.00" fill="#000000">a260_a280_ratio</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6338.5 743.1493,-6338.5 "/>
<text text-anchor="middle" x="604.6493" y="-6323.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_concentration</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6315.5 743.1493,-6315.5 "/>
<text text-anchor="middle" x="604.6493" y="-6300.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_id</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6292.5 743.1493,-6292.5 "/>
<text text-anchor="middle" x="604.6493" y="-6277.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_quantity</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6269.5 743.1493,-6269.5 "/>
<text text-anchor="middle" x="604.6493" y="-6254.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_type</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6246.5 743.1493,-6246.5 "/>
<text text-anchor="middle" x="604.6493" y="-6231.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_type_id</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6223.5 743.1493,-6223.5 "/>
<text text-anchor="middle" x="604.6493" y="-6208.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_volume</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6200.5 743.1493,-6200.5 "/>
<text text-anchor="middle" x="604.6493" y="-6185.3" font-family="Times,serif" font-size="14.00" fill="#000000">normal_tumor_genotype_snp_match</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6177.5 743.1493,-6177.5 "/>
<text text-anchor="middle" x="604.6493" y="-6162.3" font-family="Times,serif" font-size="14.00" fill="#000000">ribosomal_rna_28s_16s_ratio</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6154.5 743.1493,-6154.5 "/>
<text text-anchor="middle" x="604.6493" y="-6139.3" font-family="Times,serif" font-size="14.00" fill="#000000">spectrophotometer_method</text>
<polyline fill="none" stroke="#000000" points="466.1493,-6131.5 743.1493,-6131.5 "/>
<text text-anchor="middle" x="604.6493" y="-6116.3" font-family="Times,serif" font-size="14.00" fill="#000000">well_number</text>
<polyline fill="none" stroke="#000000" points="743.1493,-6108.5 743.1493,-6361.5 "/>
<text text-anchor="middle" x="753.6493" y="-6231.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- report&#45;&gt;analyte -->
<g id="edge11" class="edge">
<title>report&#45;&gt;analyte</title>
<path fill="none" stroke="#000000" d="M494.4147,-6821.783C488.9711,-6720.6617 485.7215,-6554.0035 510.1493,-6413 512.5011,-6399.4253 515.7106,-6385.4834 519.4307,-6371.6652"/>
<polygon fill="#000000" stroke="#000000" points="522.9136,-6372.2047 522.2249,-6361.6323 516.1702,-6370.3267 522.9136,-6372.2047"/>
<text text-anchor="middle" x="573.6493" y="-6582.3" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_analyte</text>
</g>
<!-- laboratory_procedure -->
<g id="node16" class="node">
<title>laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M623.6493,-1536.5C623.6493,-1536.5 1076.6493,-1536.5 1076.6493,-1536.5 1082.6493,-1536.5 1088.6493,-1542.5 1088.6493,-1548.5 1088.6493,-1548.5 1088.6493,-1754.5 1088.6493,-1754.5 1088.6493,-1760.5 1082.6493,-1766.5 1076.6493,-1766.5 1076.6493,-1766.5 623.6493,-1766.5 623.6493,-1766.5 617.6493,-1766.5 611.6493,-1760.5 611.6493,-1754.5 611.6493,-1754.5 611.6493,-1548.5 611.6493,-1548.5 611.6493,-1542.5 617.6493,-1536.5 623.6493,-1536.5"/>
<text text-anchor="middle" x="697.6493" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure</text>
<polyline fill="none" stroke="#000000" points="783.6493,-1536.5 783.6493,-1766.5 "/>
<text text-anchor="middle" x="794.1493" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="804.6493,-1536.5 804.6493,-1766.5 "/>
<text text-anchor="middle" x="936.1493" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1743.5 1067.6493,-1743.5 "/>
<text text-anchor="middle" x="936.1493" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_name</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1720.5 1067.6493,-1720.5 "/>
<text text-anchor="middle" x="936.1493" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_version</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1697.5 1067.6493,-1697.5 "/>
<text text-anchor="middle" x="936.1493" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure_id</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1674.5 1067.6493,-1674.5 "/>
<text text-anchor="middle" x="936.1493" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure_target_type</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1651.5 1067.6493,-1651.5 "/>
<text text-anchor="middle" x="936.1493" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure_type</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1628.5 1067.6493,-1628.5 "/>
<text text-anchor="middle" x="936.1493" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">reagent_description</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1605.5 1067.6493,-1605.5 "/>
<text text-anchor="middle" x="936.1493" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_name</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1582.5 1067.6493,-1582.5 "/>
<text text-anchor="middle" x="936.1493" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_version</text>
<polyline fill="none" stroke="#000000" points="804.6493,-1559.5 1067.6493,-1559.5 "/>
<text text-anchor="middle" x="936.1493" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_name</text>
<polyline fill="none" stroke="#000000" points="1067.6493,-1536.5 1067.6493,-1766.5 "/>
<text text-anchor="middle" x="1078.1493" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- report&#45;&gt;laboratory_procedure -->
<g id="edge18" class="edge">
<title>report&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M373.8979,-6869.8726C257.777,-6820.5432 104.1493,-6728.3764 104.1493,-6586 104.1493,-6586 104.1493,-6586 104.1493,-3394 104.1493,-2732.9784 -185.5673,-2444.6484 203.1493,-1910 295.6231,-1782.8098 461.0314,-1718.1367 601.449,-1685.2858"/>
<polygon fill="#000000" stroke="#000000" points="602.5511,-1688.6239 611.5145,-1682.9751 600.9849,-1681.8014 602.5511,-1688.6239"/>
<text text-anchor="middle" x="218.6493" y="-6078.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_laboratory_procedure</text>
</g>
<!-- fraction -->
<g id="node18" class="node">
<title>fraction</title>
<path fill="none" stroke="#000000" d="M405.1493,-5435.5C405.1493,-5435.5 643.1493,-5435.5 643.1493,-5435.5 649.1493,-5435.5 655.1493,-5441.5 655.1493,-5447.5 655.1493,-5447.5 655.1493,-5538.5 655.1493,-5538.5 655.1493,-5544.5 649.1493,-5550.5 643.1493,-5550.5 643.1493,-5550.5 405.1493,-5550.5 405.1493,-5550.5 399.1493,-5550.5 393.1493,-5544.5 393.1493,-5538.5 393.1493,-5538.5 393.1493,-5447.5 393.1493,-5447.5 393.1493,-5441.5 399.1493,-5435.5 405.1493,-5435.5"/>
<text text-anchor="middle" x="429.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">fraction</text>
<polyline fill="none" stroke="#000000" points="466.1493,-5435.5 466.1493,-5550.5 "/>
<text text-anchor="middle" x="476.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="487.1493,-5435.5 487.1493,-5550.5 "/>
<text text-anchor="middle" x="560.6493" y="-5535.3" font-family="Times,serif" font-size="14.00" fill="#000000">creation_datetime</text>
<polyline fill="none" stroke="#000000" points="487.1493,-5527.5 634.1493,-5527.5 "/>
<text text-anchor="middle" x="560.6493" y="-5512.3" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_id</text>
<polyline fill="none" stroke="#000000" points="487.1493,-5504.5 634.1493,-5504.5 "/>
<text text-anchor="middle" x="560.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_number</text>
<polyline fill="none" stroke="#000000" points="487.1493,-5481.5 634.1493,-5481.5 "/>
<text text-anchor="middle" x="560.6493" y="-5466.3" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_type</text>
<polyline fill="none" stroke="#000000" points="487.1493,-5458.5 634.1493,-5458.5 "/>
<text text-anchor="middle" x="560.6493" y="-5443.3" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="634.1493,-5435.5 634.1493,-5550.5 "/>
<text text-anchor="middle" x="644.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- report&#45;&gt;fraction -->
<g id="edge14" class="edge">
<title>report&#45;&gt;fraction</title>
<path fill="none" stroke="#000000" d="M471.6578,-6821.9631C438.5425,-6713.3768 386.8597,-6526.7476 367.1493,-6362 331.0982,-6060.6682 444.6725,-5705.7584 498.0323,-5560.2992"/>
<polygon fill="#000000" stroke="#000000" points="501.4304,-5561.2007 501.6125,-5550.6074 494.8641,-5558.775 501.4304,-5561.2007"/>
<text text-anchor="middle" x="436.1493" y="-6383.8" font-family="Times,serif" font-size="14.00" fill="#000000">report_of_fraction</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M3731.6493,-771.5C3731.6493,-771.5 4006.6493,-771.5 4006.6493,-771.5 4012.6493,-771.5 4018.6493,-777.5 4018.6493,-783.5 4018.6493,-783.5 4018.6493,-1380.5 4018.6493,-1380.5 4018.6493,-1386.5 4012.6493,-1392.5 4006.6493,-1392.5 4006.6493,-1392.5 3731.6493,-1392.5 3731.6493,-1392.5 3725.6493,-1392.5 3719.6493,-1386.5 3719.6493,-1380.5 3719.6493,-1380.5 3719.6493,-783.5 3719.6493,-783.5 3719.6493,-777.5 3725.6493,-771.5 3731.6493,-771.5"/>
<text text-anchor="middle" x="3747.6493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="3775.6493,-771.5 3775.6493,-1392.5 "/>
<text text-anchor="middle" x="3786.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3796.6493,-771.5 3796.6493,-1392.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1377.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_type</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1369.5 3997.6493,-1369.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fraction</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1346.5 3997.6493,-1346.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1331.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_approval</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1323.5 3997.6493,-1323.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1308.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession_number</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1300.5 3997.6493,-1300.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1285.3" font-family="Times,serif" font-size="14.00" fill="#000000">embargo_date</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1277.5 3997.6493,-1277.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1262.3" font-family="Times,serif" font-size="14.00" fill="#000000">end_date</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1254.5 3997.6493,-1254.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1239.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_review</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1231.5 3997.6493,-1231.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1208.5 3997.6493,-1208.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">intended_release_date</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1185.5 3997.6493,-1185.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_legacy</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1162.5 3997.6493,-1162.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1139.5 3997.6493,-1139.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">releasable</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1116.5 3997.6493,-1116.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_requested</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1093.5 3997.6493,-1093.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">released</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1070.5 3997.6493,-1070.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">request_submission</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1047.5 3997.6493,-1047.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_date</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1024.5 3997.6493,-1024.5 "/>
<text text-anchor="middle" x="3897.1493" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">state</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-1001.5 3997.6493,-1001.5 "/>
<text text-anchor="middle" x="3897.1493" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-978.5 3997.6493,-978.5 "/>
<text text-anchor="middle" x="3897.1493" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-955.5 3997.6493,-955.5 "/>
<text text-anchor="middle" x="3897.1493" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_full_description</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-932.5 3997.6493,-932.5 "/>
<text text-anchor="middle" x="3897.1493" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-909.5 3997.6493,-909.5 "/>
<text text-anchor="middle" x="3897.1493" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_manager</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-886.5 3997.6493,-886.5 "/>
<text text-anchor="middle" x="3897.1493" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-863.5 3997.6493,-863.5 "/>
<text text-anchor="middle" x="3897.1493" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_description</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-840.5 3997.6493,-840.5 "/>
<text text-anchor="middle" x="3897.1493" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_sort_order</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-817.5 3997.6493,-817.5 "/>
<text text-anchor="middle" x="3897.1493" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="3796.6493,-794.5 3997.6493,-794.5 "/>
<text text-anchor="middle" x="3897.1493" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_enabled</text>
<polyline fill="none" stroke="#000000" points="3997.6493,-771.5 3997.6493,-1392.5 "/>
<text text-anchor="middle" x="4008.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program -->
<g id="node4" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M3392.1493,-144.5C3392.1493,-144.5 3700.1493,-144.5 3700.1493,-144.5 3706.1493,-144.5 3712.1493,-150.5 3712.1493,-156.5 3712.1493,-156.5 3712.1493,-707.5 3712.1493,-707.5 3712.1493,-713.5 3706.1493,-719.5 3700.1493,-719.5 3700.1493,-719.5 3392.1493,-719.5 3392.1493,-719.5 3386.1493,-719.5 3380.1493,-713.5 3380.1493,-707.5 3380.1493,-707.5 3380.1493,-156.5 3380.1493,-156.5 3380.1493,-150.5 3386.1493,-144.5 3392.1493,-144.5"/>
<text text-anchor="middle" x="3419.1493" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="3458.1493,-144.5 3458.1493,-719.5 "/>
<text text-anchor="middle" x="3468.6493" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3479.1493,-144.5 3479.1493,-719.5 "/>
<text text-anchor="middle" x="3585.1493" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_approval</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-696.5 3691.1493,-696.5 "/>
<text text-anchor="middle" x="3585.1493" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession_number</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-673.5 3691.1493,-673.5 "/>
<text text-anchor="middle" x="3585.1493" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">embargo_date</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-650.5 3691.1493,-650.5 "/>
<text text-anchor="middle" x="3585.1493" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">end_date</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-627.5 3691.1493,-627.5 "/>
<text text-anchor="middle" x="3585.1493" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_review</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-604.5 3691.1493,-604.5 "/>
<text text-anchor="middle" x="3585.1493" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-581.5 3691.1493,-581.5 "/>
<text text-anchor="middle" x="3585.1493" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">intended_release_date</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-558.5 3691.1493,-558.5 "/>
<text text-anchor="middle" x="3585.1493" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_legacy</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-535.5 3691.1493,-535.5 "/>
<text text-anchor="middle" x="3585.1493" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-512.5 3691.1493,-512.5 "/>
<text text-anchor="middle" x="3585.1493" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-489.5 3691.1493,-489.5 "/>
<text text-anchor="middle" x="3585.1493" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-466.5 3691.1493,-466.5 "/>
<text text-anchor="middle" x="3585.1493" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_id</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-443.5 3691.1493,-443.5 "/>
<text text-anchor="middle" x="3585.1493" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_manager</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-420.5 3691.1493,-420.5 "/>
<text text-anchor="middle" x="3585.1493" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-397.5 3691.1493,-397.5 "/>
<text text-anchor="middle" x="3585.1493" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-374.5 3691.1493,-374.5 "/>
<text text-anchor="middle" x="3585.1493" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-351.5 3691.1493,-351.5 "/>
<text text-anchor="middle" x="3585.1493" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-328.5 3691.1493,-328.5 "/>
<text text-anchor="middle" x="3585.1493" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">releasable</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-305.5 3691.1493,-305.5 "/>
<text text-anchor="middle" x="3585.1493" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_requested</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-282.5 3691.1493,-282.5 "/>
<text text-anchor="middle" x="3585.1493" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">released</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-259.5 3691.1493,-259.5 "/>
<text text-anchor="middle" x="3585.1493" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">request_submission</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-236.5 3691.1493,-236.5 "/>
<text text-anchor="middle" x="3585.1493" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">sponsor</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-213.5 3691.1493,-213.5 "/>
<text text-anchor="middle" x="3585.1493" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_date</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-190.5 3691.1493,-190.5 "/>
<text text-anchor="middle" x="3585.1493" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">state</text>
<polyline fill="none" stroke="#000000" points="3479.1493,-167.5 3691.1493,-167.5 "/>
<text text-anchor="middle" x="3585.1493" y="-152.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_enabled</text>
<polyline fill="none" stroke="#000000" points="3691.1493,-144.5 3691.1493,-719.5 "/>
<text text-anchor="middle" x="3701.6493" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge33" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M3719.4686,-780.7848C3710.8965,-763.5345 3702.2797,-746.1943 3693.7156,-728.9601"/>
<polygon fill="#000000" stroke="#000000" points="3696.827,-727.3561 3689.2425,-719.9584 3690.5583,-730.4712 3696.827,-727.3561"/>
<text text-anchor="middle" x="3767.1493" y="-741.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_of_program</text>
</g>
<!-- institution -->
<g id="node3" class="node">
<title>institution</title>
<path fill="none" stroke="#000000" d="M3406.6493,-.5C3406.6493,-.5 3685.6493,-.5 3685.6493,-.5 3691.6493,-.5 3697.6493,-6.5 3697.6493,-12.5 3697.6493,-12.5 3697.6493,-80.5 3697.6493,-80.5 3697.6493,-86.5 3691.6493,-92.5 3685.6493,-92.5 3685.6493,-92.5 3406.6493,-92.5 3406.6493,-92.5 3400.6493,-92.5 3394.6493,-86.5 3394.6493,-80.5 3394.6493,-80.5 3394.6493,-12.5 3394.6493,-12.5 3394.6493,-6.5 3400.6493,-.5 3406.6493,-.5"/>
<text text-anchor="middle" x="3440.1493" y="-42.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="3485.6493,-.5 3485.6493,-92.5 "/>
<text text-anchor="middle" x="3496.1493" y="-42.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3506.6493,-.5 3506.6493,-92.5 "/>
<text text-anchor="middle" x="3591.6493" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution_acronymn</text>
<polyline fill="none" stroke="#000000" points="3506.6493,-69.5 3676.6493,-69.5 "/>
<text text-anchor="middle" x="3591.6493" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution_id</text>
<polyline fill="none" stroke="#000000" points="3506.6493,-46.5 3676.6493,-46.5 "/>
<text text-anchor="middle" x="3591.6493" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution_name</text>
<polyline fill="none" stroke="#000000" points="3506.6493,-23.5 3676.6493,-23.5 "/>
<text text-anchor="middle" x="3591.6493" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution_url</text>
<polyline fill="none" stroke="#000000" points="3676.6493,-.5 3676.6493,-92.5 "/>
<text text-anchor="middle" x="3687.1493" y="-42.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program&#45;&gt;institution -->
<g id="edge28" class="edge">
<title>program&#45;&gt;institution</title>
<path fill="none" stroke="#000000" d="M3546.1493,-144.2763C3546.1493,-129.2309 3546.1493,-115.2147 3546.1493,-102.7601"/>
<polygon fill="#000000" stroke="#000000" points="3549.6494,-102.6771 3546.1493,-92.6771 3542.6494,-102.6772 3549.6494,-102.6771"/>
<text text-anchor="middle" x="3628.6493" y="-114.8" font-family="Times,serif" font-size="14.00" fill="#000000">program_of_institution</text>
</g>
<!-- sample&#45;&gt;laboratory_procedure -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M1030.6103,-2899.3304C974.9786,-2514.6549 901.8075,-2008.6995 868.3097,-1777.0732"/>
<polygon fill="#000000" stroke="#000000" points="871.7376,-1776.3223 866.8423,-1766.9262 864.8097,-1777.3242 871.7376,-1776.3223"/>
<text text-anchor="middle" x="961.6493" y="-1880.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_processed_by</text>
</g>
<!-- study_subject -->
<g id="node20" class="node">
<title>study_subject</title>
<path fill="none" stroke="#000000" d="M2554.6493,-1444.5C2554.6493,-1444.5 2911.6493,-1444.5 2911.6493,-1444.5 2917.6493,-1444.5 2923.6493,-1450.5 2923.6493,-1456.5 2923.6493,-1456.5 2923.6493,-1846.5 2923.6493,-1846.5 2923.6493,-1852.5 2917.6493,-1858.5 2911.6493,-1858.5 2911.6493,-1858.5 2554.6493,-1858.5 2554.6493,-1858.5 2548.6493,-1858.5 2542.6493,-1852.5 2542.6493,-1846.5 2542.6493,-1846.5 2542.6493,-1456.5 2542.6493,-1456.5 2542.6493,-1450.5 2548.6493,-1444.5 2554.6493,-1444.5"/>
<text text-anchor="middle" x="2600.6493" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject</text>
<polyline fill="none" stroke="#000000" points="2658.6493,-1444.5 2658.6493,-1858.5 "/>
<text text-anchor="middle" x="2669.1493" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1444.5 2679.6493,-1858.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1843.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_report_form_submitted</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1835.5 2902.6493,-1835.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1820.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_type</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1812.5 2902.6493,-1812.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1789.5 2902.6493,-1789.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_consent</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1766.5 2902.6493,-1766.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_lost_to_followup</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1743.5 2902.6493,-1743.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_subtype</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1720.5 2902.6493,-1720.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1697.5 2902.6493,-1697.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_analysis</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1674.5 2902.6493,-1674.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1651.5 2902.6493,-1651.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_followup</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1628.5 2902.6493,-1628.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">pool</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1605.5 2902.6493,-1605.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1582.5 2902.6493,-1582.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1559.5 2902.6493,-1559.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_first_name</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1536.5 2902.6493,-1536.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_id</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1513.5 2902.6493,-1513.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_is_ref</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1490.5 2902.6493,-1490.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_source_id</text>
<polyline fill="none" stroke="#000000" points="2679.6493,-1467.5 2902.6493,-1467.5 "/>
<text text-anchor="middle" x="2791.1493" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">taxon</text>
<polyline fill="none" stroke="#000000" points="2902.6493,-1444.5 2902.6493,-1858.5 "/>
<text text-anchor="middle" x="2913.1493" y="-1647.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study_subject -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M987.9305,-2899.4628C942.7989,-2568.6279 950.382,-2146.1445 1198.1493,-1877 1287.3692,-1780.0823 2136.5941,-1699.6064 2532.1842,-1667.0388"/>
<polygon fill="#000000" stroke="#000000" points="2532.6306,-1670.514 2542.3106,-1666.2074 2532.0577,-1663.5375 2532.6306,-1670.514"/>
<text text-anchor="middle" x="1288.1493" y="-1880.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_of_study_subject</text>
</g>
<!-- demographic_data -->
<g id="node6" class="node">
<title>demographic_data</title>
<path fill="none" stroke="#000000" d="M3049.6493,-3129.5C3049.6493,-3129.5 3426.6493,-3129.5 3426.6493,-3129.5 3432.6493,-3129.5 3438.6493,-3135.5 3438.6493,-3141.5 3438.6493,-3141.5 3438.6493,-3646.5 3438.6493,-3646.5 3438.6493,-3652.5 3432.6493,-3658.5 3426.6493,-3658.5 3426.6493,-3658.5 3049.6493,-3658.5 3049.6493,-3658.5 3043.6493,-3658.5 3037.6493,-3652.5 3037.6493,-3646.5 3037.6493,-3646.5 3037.6493,-3141.5 3037.6493,-3141.5 3037.6493,-3135.5 3043.6493,-3129.5 3049.6493,-3129.5"/>
<text text-anchor="middle" x="3112.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic_data</text>
<polyline fill="none" stroke="#000000" points="3186.6493,-3129.5 3186.6493,-3658.5 "/>
<text text-anchor="middle" x="3197.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3129.5 3207.6493,-3658.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3643.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_index</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3635.5 3417.6493,-3635.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3620.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_is_obfuscated</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3612.5 3417.6493,-3612.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3597.3" font-family="Times,serif" font-size="14.00" fill="#000000">breed</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3589.5 3417.6493,-3589.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3574.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3566.5 3417.6493,-3566.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3551.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death_source</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3543.5 3417.6493,-3543.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3528.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_birth</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3520.5 3417.6493,-3520.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3505.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_birth</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3497.5 3417.6493,-3497.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3482.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_death</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3474.5 3417.6493,-3474.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3459.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic_data_id</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3451.5 3417.6493,-3451.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3436.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3428.5 3417.6493,-3428.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3413.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3405.5 3417.6493,-3405.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">height</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3382.5 3417.6493,-3382.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3367.3" font-family="Times,serif" font-size="14.00" fill="#000000">menopause_status</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3359.5 3417.6493,-3359.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3344.3" font-family="Times,serif" font-size="14.00" fill="#000000">neutered_indicator</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3336.5 3417.6493,-3336.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3321.3" font-family="Times,serif" font-size="14.00" fill="#000000">occupation_duration_years</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3313.5 3417.6493,-3313.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3298.3" font-family="Times,serif" font-size="14.00" fill="#000000">premature_at_birth</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3290.5 3417.6493,-3290.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3275.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3267.5 3417.6493,-3267.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3252.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_time</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3244.5 3417.6493,-3244.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3229.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3221.5 3417.6493,-3221.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3206.3" font-family="Times,serif" font-size="14.00" fill="#000000">weeks_gestation_at_birth</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3198.5 3417.6493,-3198.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3183.3" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3175.5 3417.6493,-3175.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3160.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_birth</text>
<polyline fill="none" stroke="#000000" points="3207.6493,-3152.5 3417.6493,-3152.5 "/>
<text text-anchor="middle" x="3312.6493" y="-3137.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_death</text>
<polyline fill="none" stroke="#000000" points="3417.6493,-3129.5 3417.6493,-3658.5 "/>
<text text-anchor="middle" x="3428.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic_data&#45;&gt;study_subject -->
<g id="edge39" class="edge">
<title>demographic_data&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M3254.7286,-3129.2406C3262.522,-2818.3648 3238.3406,-2296.2022 3029.1493,-1910 3004.8542,-1865.1471 2969.5026,-1824.4443 2931.6251,-1789.2932"/>
<polygon fill="#000000" stroke="#000000" points="2933.7601,-1786.5028 2924.0184,-1782.3374 2929.0363,-1791.6686 2933.7601,-1786.5028"/>
<text text-anchor="middle" x="3129.6493" y="-1880.8" font-family="Times,serif" font-size="14.00" fill="#000000">demographic_of_study_subject</text>
</g>
<!-- follow_up -->
<g id="node7" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2114.6493,-4929.5C2114.6493,-4929.5 2535.6493,-4929.5 2535.6493,-4929.5 2541.6493,-4929.5 2547.6493,-4935.5 2547.6493,-4941.5 2547.6493,-4941.5 2547.6493,-6044.5 2547.6493,-6044.5 2547.6493,-6050.5 2541.6493,-6056.5 2535.6493,-6056.5 2535.6493,-6056.5 2114.6493,-6056.5 2114.6493,-6056.5 2108.6493,-6056.5 2102.6493,-6050.5 2102.6493,-6044.5 2102.6493,-6044.5 2102.6493,-4941.5 2102.6493,-4941.5 2102.6493,-4935.5 2108.6493,-4929.5 2114.6493,-4929.5"/>
<text text-anchor="middle" x="2145.1493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2187.6493,-4929.5 2187.6493,-6056.5 "/>
<text text-anchor="middle" x="2198.1493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2208.6493,-4929.5 2208.6493,-6056.5 "/>
<text text-anchor="middle" x="2367.6493" y="-6041.3" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-6033.5 2526.6493,-6033.5 "/>
<text text-anchor="middle" x="2367.6493" y="-6018.3" font-family="Times,serif" font-size="14.00" fill="#000000">barretts_esophagus_goblet_cells_present</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-6010.5 2526.6493,-6010.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5995.3" font-family="Times,serif" font-size="14.00" fill="#000000">bmi</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5987.5 2526.6493,-5987.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5972.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_response</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5964.5 2526.6493,-5964.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5949.3" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5941.5 2526.6493,-5941.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5926.3" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5918.5 2526.6493,-5918.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5903.3" font-family="Times,serif" font-size="14.00" fill="#000000">contact_type</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5895.5 2526.6493,-5895.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5880.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_contact</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5872.5 2526.6493,-5872.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5857.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_adverse_event</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5849.5 2526.6493,-5849.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5834.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_comorbidity</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5826.5 2526.6493,-5826.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5811.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_distant_recurrence</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5803.5 2526.6493,-5803.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5788.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5780.5 2526.6493,-5780.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5765.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_progression</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5757.5 2526.6493,-5757.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5742.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_progression_free</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5734.5 2526.6493,-5734.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5719.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5711.5 2526.6493,-5711.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5696.3" font-family="Times,serif" font-size="14.00" fill="#000000">dfs_event_indicator</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5688.5 2526.6493,-5688.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5673.3" font-family="Times,serif" font-size="14.00" fill="#000000">dfs_event_type</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5665.5 2526.6493,-5665.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5650.3" font-family="Times,serif" font-size="14.00" fill="#000000">diabetes_treatment_type</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5642.5 2526.6493,-5642.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5627.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5619.5 2526.6493,-5619.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5604.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5596.5 2526.6493,-5596.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5581.3" font-family="Times,serif" font-size="14.00" fill="#000000">dlco_ref_predictive_percent</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5573.5 2526.6493,-5573.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5558.3" font-family="Times,serif" font-size="14.00" fill="#000000">document_number</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5550.5 2526.6493,-5550.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5535.3" font-family="Times,serif" font-size="14.00" fill="#000000">ecog_performance_status</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5527.5 2526.6493,-5527.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5512.3" font-family="Times,serif" font-size="14.00" fill="#000000">explain_unknown_status</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5504.5 2526.6493,-5504.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">fev1_fvc_post_bronch_percent</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5481.5 2526.6493,-5481.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5466.3" font-family="Times,serif" font-size="14.00" fill="#000000">fev1_fvc_pre_bronch_percent</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5458.5 2526.6493,-5458.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5443.3" font-family="Times,serif" font-size="14.00" fill="#000000">fev1_ref_post_bronch_percent</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5435.5 2526.6493,-5435.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5420.3" font-family="Times,serif" font-size="14.00" fill="#000000">fev1_ref_pre_bronch_percent</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5412.5 2526.6493,-5412.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5397.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_recurrence_type</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5389.5 2526.6493,-5389.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5374.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5366.5 2526.6493,-5366.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5351.3" font-family="Times,serif" font-size="14.00" fill="#000000">height</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5343.5 2526.6493,-5343.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5328.3" font-family="Times,serif" font-size="14.00" fill="#000000">hepatitis_sustained_virological_response</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5320.5 2526.6493,-5320.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5305.3" font-family="Times,serif" font-size="14.00" fill="#000000">hpv_positive_type</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5297.5 2526.6493,-5297.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5282.3" font-family="Times,serif" font-size="14.00" fill="#000000">karnofsky_performance_status</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5274.5 2526.6493,-5274.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5259.3" font-family="Times,serif" font-size="14.00" fill="#000000">menopause_status</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5251.5 2526.6493,-5251.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5236.3" font-family="Times,serif" font-size="14.00" fill="#000000">pancreatitis_onset_year</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5228.5 2526.6493,-5228.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5213.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_status</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5205.5 2526.6493,-5205.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5190.3" font-family="Times,serif" font-size="14.00" fill="#000000">physical_exam_changes</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5182.5 2526.6493,-5182.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5167.3" font-family="Times,serif" font-size="14.00" fill="#000000">physical_exam_performed</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5159.5 2526.6493,-5159.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5144.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5136.5 2526.6493,-5136.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5121.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5113.5 2526.6493,-5113.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5098.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence_type</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5090.5 2526.6493,-5090.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5075.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_free_indicator</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5067.5 2526.6493,-5067.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5052.3" font-family="Times,serif" font-size="14.00" fill="#000000">reflux_treatment_type</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5044.5 2526.6493,-5044.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5029.3" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-5021.5 2526.6493,-5021.5 "/>
<text text-anchor="middle" x="2367.6493" y="-5006.3" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor_treatment</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-4998.5 2526.6493,-4998.5 "/>
<text text-anchor="middle" x="2367.6493" y="-4983.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_since_last_contact</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-4975.5 2526.6493,-4975.5 "/>
<text text-anchor="middle" x="2367.6493" y="-4960.3" font-family="Times,serif" font-size="14.00" fill="#000000">viral_hepatitis_serologies</text>
<polyline fill="none" stroke="#000000" points="2208.6493,-4952.5 2526.6493,-4952.5 "/>
<text text-anchor="middle" x="2367.6493" y="-4937.3" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="2526.6493,-4929.5 2526.6493,-6056.5 "/>
<text text-anchor="middle" x="2537.1493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2586.1493,-1910.5C2586.1493,-1910.5 3008.1493,-1910.5 3008.1493,-1910.5 3014.1493,-1910.5 3020.1493,-1916.5 3020.1493,-1922.5 3020.1493,-1922.5 3020.1493,-4865.5 3020.1493,-4865.5 3020.1493,-4871.5 3014.1493,-4877.5 3008.1493,-4877.5 3008.1493,-4877.5 2586.1493,-4877.5 2586.1493,-4877.5 2580.1493,-4877.5 2574.1493,-4871.5 2574.1493,-4865.5 2574.1493,-4865.5 2574.1493,-1922.5 2574.1493,-1922.5 2574.1493,-1916.5 2580.1493,-1910.5 2586.1493,-1910.5"/>
<text text-anchor="middle" x="2616.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2658.1493,-1910.5 2658.1493,-4877.5 "/>
<text text-anchor="middle" x="2668.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2679.1493,-1910.5 2679.1493,-4877.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4862.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4854.5 2999.1493,-4854.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4839.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4831.5 2999.1493,-4831.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4816.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4808.5 2999.1493,-4808.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4793.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_clinical_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4785.5 2999.1493,-4785.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4770.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4762.5 2999.1493,-4762.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4747.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_pathologic_m</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4739.5 2999.1493,-4739.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4724.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_pathologic_n</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4716.5 2999.1493,-4716.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4701.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_pathologic_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4693.5 2999.1493,-4693.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4678.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_pathologic_t</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4670.5 2999.1493,-4670.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4655.3" font-family="Times,serif" font-size="14.00" fill="#000000">ajcc_staging_system_edition</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4647.5 2999.1493,-4647.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4632.3" font-family="Times,serif" font-size="14.00" fill="#000000">anaplasia_present</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4624.5 2999.1493,-4624.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4609.3" font-family="Times,serif" font-size="14.00" fill="#000000">anaplasia_present_type</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4601.5 2999.1493,-4601.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4586.3" font-family="Times,serif" font-size="14.00" fill="#000000">ann_arbor_b_symptoms</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4578.5 2999.1493,-4578.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4563.3" font-family="Times,serif" font-size="14.00" fill="#000000">ann_arbor_clinical_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4555.5 2999.1493,-4555.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4540.3" font-family="Times,serif" font-size="14.00" fill="#000000">ann_arbor_extranodal_involvement</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4532.5 2999.1493,-4532.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4517.3" font-family="Times,serif" font-size="14.00" fill="#000000">ann_arbor_pathologic_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4509.5 2999.1493,-4509.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4494.3" font-family="Times,serif" font-size="14.00" fill="#000000">best_overall_response</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4486.5 2999.1493,-4486.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4471.3" font-family="Times,serif" font-size="14.00" fill="#000000">breslow_thickness</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4463.5 2999.1493,-4463.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4448.3" font-family="Times,serif" font-size="14.00" fill="#000000">burkitt_lymphoma_clinical_variant</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4440.5 2999.1493,-4440.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4425.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4417.5 2999.1493,-4417.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4402.3" font-family="Times,serif" font-size="14.00" fill="#000000">child_pugh_classification</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4394.5 2999.1493,-4394.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4379.3" font-family="Times,serif" font-size="14.00" fill="#000000">circumferential_resection_margin</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4371.5 2999.1493,-4371.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4356.3" font-family="Times,serif" font-size="14.00" fill="#000000">classification_of_tumor</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4348.5 2999.1493,-4348.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4333.3" font-family="Times,serif" font-size="14.00" fill="#000000">cog_liver_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4325.5 2999.1493,-4325.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4310.3" font-family="Times,serif" font-size="14.00" fill="#000000">cog_neuroblastoma_risk_group</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4302.5 2999.1493,-4302.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4287.3" font-family="Times,serif" font-size="14.00" fill="#000000">cog_renal_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4279.5 2999.1493,-4279.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4264.3" font-family="Times,serif" font-size="14.00" fill="#000000">cog_rhabdomyosarcoma_risk_group</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4256.5 2999.1493,-4256.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4241.3" font-family="Times,serif" font-size="14.00" fill="#000000">colon_polyps_history</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4233.5 2999.1493,-4233.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4218.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4210.5 2999.1493,-4210.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4195.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease_type</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4187.5 2999.1493,-4187.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4172.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4164.5 2999.1493,-4164.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4149.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_histology_confirmation</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4141.5 2999.1493,-4141.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4126.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_best_overall_response</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4118.5 2999.1493,-4118.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4103.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_birth</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4095.5 2999.1493,-4095.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4080.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_death</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4072.5 2999.1493,-4072.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4057.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4049.5 2999.1493,-4049.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4034.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_hiv_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4026.5 2999.1493,-4026.5 "/>
<text text-anchor="middle" x="2839.1493" y="-4011.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_follow_up</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-4003.5 2999.1493,-4003.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3988.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3980.5 2999.1493,-3980.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3965.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_new_event</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3957.5 2999.1493,-3957.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3942.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3934.5 2999.1493,-3934.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3919.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3911.5 2999.1493,-3911.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3896.3" font-family="Times,serif" font-size="14.00" fill="#000000">enneking_msts_grade</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3888.5 2999.1493,-3888.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3873.3" font-family="Times,serif" font-size="14.00" fill="#000000">enneking_msts_metastasis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3865.5 2999.1493,-3865.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3850.3" font-family="Times,serif" font-size="14.00" fill="#000000">enneking_msts_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3842.5 2999.1493,-3842.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3827.3" font-family="Times,serif" font-size="14.00" fill="#000000">enneking_msts_tumor_site</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3819.5 2999.1493,-3819.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3804.3" font-family="Times,serif" font-size="14.00" fill="#000000">er_status</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3796.5 2999.1493,-3796.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3781.3" font-family="Times,serif" font-size="14.00" fill="#000000">esophageal_columnar_dysplasia_degree</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3773.5 2999.1493,-3773.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3758.3" font-family="Times,serif" font-size="14.00" fill="#000000">esophageal_columnar_metaplasia_present</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3750.5 2999.1493,-3750.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3735.3" font-family="Times,serif" font-size="14.00" fill="#000000">figo_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3727.5 2999.1493,-3727.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3712.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_symptom_prior_to_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3704.5 2999.1493,-3704.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3689.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_data</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3681.5 2999.1493,-3681.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3666.3" font-family="Times,serif" font-size="14.00" fill="#000000">gastric_esophageal_junction_involvement</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3658.5 2999.1493,-3658.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3643.3" font-family="Times,serif" font-size="14.00" fill="#000000">gleason_grade_group</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3635.5 2999.1493,-3635.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3620.3" font-family="Times,serif" font-size="14.00" fill="#000000">goblet_cells_columnar_mucosa_present</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3612.5 2999.1493,-3612.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3597.3" font-family="Times,serif" font-size="14.00" fill="#000000">gross_tumor_weight</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3589.5 2999.1493,-3589.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3574.3" font-family="Times,serif" font-size="14.00" fill="#000000">hiv_positive</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3566.5 2999.1493,-3566.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3551.3" font-family="Times,serif" font-size="14.00" fill="#000000">hpv_positive_type</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3543.5 2999.1493,-3543.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3528.3" font-family="Times,serif" font-size="14.00" fill="#000000">hpv_status</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3520.5 2999.1493,-3520.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3505.3" font-family="Times,serif" font-size="14.00" fill="#000000">icd_10_code</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3497.5 2999.1493,-3497.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3482.3" font-family="Times,serif" font-size="14.00" fill="#000000">igcccg_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3474.5 2999.1493,-3474.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3459.3" font-family="Times,serif" font-size="14.00" fill="#000000">inpc_grade</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3451.5 2999.1493,-3451.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3436.3" font-family="Times,serif" font-size="14.00" fill="#000000">inpc_histologic_group</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3428.5 2999.1493,-3428.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3413.3" font-family="Times,serif" font-size="14.00" fill="#000000">inrg_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3405.5 2999.1493,-3405.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">inss_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3382.5 2999.1493,-3382.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3367.3" font-family="Times,serif" font-size="14.00" fill="#000000">international_prognostic_index</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3359.5 2999.1493,-3359.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3344.3" font-family="Times,serif" font-size="14.00" fill="#000000">irs_group</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3336.5 2999.1493,-3336.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3321.3" font-family="Times,serif" font-size="14.00" fill="#000000">irs_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3313.5 2999.1493,-3313.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3298.3" font-family="Times,serif" font-size="14.00" fill="#000000">ishak_fibrosis_score</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3290.5 2999.1493,-3290.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3275.3" font-family="Times,serif" font-size="14.00" fill="#000000">iss_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3267.5 2999.1493,-3267.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3252.3" font-family="Times,serif" font-size="14.00" fill="#000000">largest_extrapelvic_peritoneal_focus</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3244.5 2999.1493,-3244.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3229.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3221.5 2999.1493,-3221.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3206.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3198.5 2999.1493,-3198.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3183.3" font-family="Times,serif" font-size="14.00" fill="#000000">ldh_level_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3175.5 2999.1493,-3175.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3160.3" font-family="Times,serif" font-size="14.00" fill="#000000">ldh_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3152.5 2999.1493,-3152.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3137.3" font-family="Times,serif" font-size="14.00" fill="#000000">lymph_nodes_positive</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3129.5 2999.1493,-3129.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3114.3" font-family="Times,serif" font-size="14.00" fill="#000000">lymph_nodes_tested</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3106.5 2999.1493,-3106.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3091.3" font-family="Times,serif" font-size="14.00" fill="#000000">lymphatic_invasion_present</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3083.5 2999.1493,-3083.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3068.3" font-family="Times,serif" font-size="14.00" fill="#000000">masaoka_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3060.5 2999.1493,-3060.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3045.3" font-family="Times,serif" font-size="14.00" fill="#000000">medulloblastoma_molecular_classification</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3037.5 2999.1493,-3037.5 "/>
<text text-anchor="middle" x="2839.1493" y="-3022.3" font-family="Times,serif" font-size="14.00" fill="#000000">metastasis_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-3014.5 2999.1493,-3014.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2999.3" font-family="Times,serif" font-size="14.00" fill="#000000">metastasis_at_diagnosis_site</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2991.5 2999.1493,-2991.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2976.3" font-family="Times,serif" font-size="14.00" fill="#000000">method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2968.5 2999.1493,-2968.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2953.3" font-family="Times,serif" font-size="14.00" fill="#000000">micropapillary_features</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2945.5 2999.1493,-2945.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2930.3" font-family="Times,serif" font-size="14.00" fill="#000000">mitosis_karyorrhexis_index</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2922.5 2999.1493,-2922.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2907.3" font-family="Times,serif" font-size="14.00" fill="#000000">mitotic_count</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2899.5 2999.1493,-2899.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2884.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2876.5 2999.1493,-2876.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2861.3" font-family="Times,serif" font-size="14.00" fill="#000000">new_event_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2853.5 2999.1493,-2853.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2838.3" font-family="Times,serif" font-size="14.00" fill="#000000">new_event_type</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2830.5 2999.1493,-2830.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2815.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_nodal_regional_disease</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2807.5 2999.1493,-2807.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2792.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_nodal_tumor_deposits</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2784.5 2999.1493,-2784.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2769.3" font-family="Times,serif" font-size="14.00" fill="#000000">nuclear_grade</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2761.5 2999.1493,-2761.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2746.3" font-family="Times,serif" font-size="14.00" fill="#000000">ovarian_specimen_status</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2738.5 2999.1493,-2738.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2723.3" font-family="Times,serif" font-size="14.00" fill="#000000">ovarian_surface_involvement</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2715.5 2999.1493,-2715.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2700.3" font-family="Times,serif" font-size="14.00" fill="#000000">overall_survival</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2692.5 2999.1493,-2692.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2677.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_report</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2669.5 2999.1493,-2669.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2654.3" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor_invasion</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2646.5 2999.1493,-2646.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2631.3" font-family="Times,serif" font-size="14.00" fill="#000000">perineural_invasion_present</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2623.5 2999.1493,-2623.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2608.3" font-family="Times,serif" font-size="14.00" fill="#000000">peripancreatic_lymph_nodes_positive</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2600.5 2999.1493,-2600.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2585.3" font-family="Times,serif" font-size="14.00" fill="#000000">peripancreatic_lymph_nodes_tested</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2577.5 2999.1493,-2577.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2562.3" font-family="Times,serif" font-size="14.00" fill="#000000">peritoneal_fluid_cytological_status</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2554.5 2999.1493,-2554.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2539.3" font-family="Times,serif" font-size="14.00" fill="#000000">pr_status</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2531.5 2999.1493,-2531.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2516.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2508.5 2999.1493,-2508.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2493.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_gleason_grade</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2485.5 2999.1493,-2485.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2470.3" font-family="Times,serif" font-size="14.00" fill="#000000">prior_malignancy</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2462.5 2999.1493,-2462.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2447.3" font-family="Times,serif" font-size="14.00" fill="#000000">prior_treatment</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2439.5 2999.1493,-2439.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2424.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_free_survival</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2416.5 2999.1493,-2416.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2401.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_free_survival_event</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2393.5 2999.1493,-2393.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2378.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2370.5 2999.1493,-2370.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2355.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_score</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2347.5 2999.1493,-2347.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2332.3" font-family="Times,serif" font-size="14.00" fill="#000000">residual_disease</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2324.5 2999.1493,-2324.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2309.3" font-family="Times,serif" font-size="14.00" fill="#000000">secondary_gleason_grade</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2301.5 2999.1493,-2301.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2286.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2278.5 2999.1493,-2278.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2263.3" font-family="Times,serif" font-size="14.00" fill="#000000">supratentorial_localization</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2255.5 2999.1493,-2255.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2240.3" font-family="Times,serif" font-size="14.00" fill="#000000">synchronous_malignancy</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2232.5 2999.1493,-2232.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2217.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2209.5 2999.1493,-2209.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2194.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_data</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2186.5 2999.1493,-2186.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2171.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_confined_to_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2163.5 2999.1493,-2163.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2148.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_focality</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2140.5 2999.1493,-2140.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2125.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2117.5 2999.1493,-2117.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2102.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_largest_dimension_diameter</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2094.5 2999.1493,-2094.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2079.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_regression_grade</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2071.5 2999.1493,-2071.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2056.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_group</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2048.5 2999.1493,-2048.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2033.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2025.5 2999.1493,-2025.5 "/>
<text text-anchor="middle" x="2839.1493" y="-2010.3" font-family="Times,serif" font-size="14.00" fill="#000000">vascular_invasion_present</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-2002.5 2999.1493,-2002.5 "/>
<text text-anchor="middle" x="2839.1493" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">vascular_invasion_type</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-1979.5 2999.1493,-1979.5 "/>
<text text-anchor="middle" x="2839.1493" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">weiss_assessment_score</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-1956.5 2999.1493,-1956.5 "/>
<text text-anchor="middle" x="2839.1493" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">wilms_tumor_histologic_subtype</text>
<polyline fill="none" stroke="#000000" points="2679.1493,-1933.5 2999.1493,-1933.5 "/>
<text text-anchor="middle" x="2839.1493" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2999.1493,-1910.5 2999.1493,-4877.5 "/>
<text text-anchor="middle" x="3009.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;diagnosis -->
<g id="edge1" class="edge">
<title>follow_up&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M2545.6582,-4929.3813C2550.7551,-4912.1301 2555.603,-4894.9754 2560.1493,-4878 2563.9882,-4863.6663 2567.7735,-4849.2369 2571.5057,-4834.7234"/>
<polygon fill="#000000" stroke="#000000" points="2574.9919,-4835.2178 2574.081,-4824.6622 2568.2105,-4833.4819 2574.9919,-4835.2178"/>
<text text-anchor="middle" x="2607.6493" y="-4899.8" font-family="Times,serif" font-size="14.00" fill="#000000">fu_of_diagnosis</text>
</g>
<!-- follow_up&#45;&gt;study_subject -->
<g id="edge5" class="edge">
<title>follow_up&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M2383.0084,-4929.279C2384.1591,-4911.9975 2385.212,-4894.8729 2386.1493,-4878 2390.7227,-4795.6764 2386.6782,-1984.4304 2422.1493,-1910 2447.4187,-1856.9764 2489.3859,-1811.0018 2534.4386,-1773.1318"/>
<polygon fill="#000000" stroke="#000000" points="2536.8111,-1775.7115 2542.286,-1766.6409 2532.3495,-1770.3176 2536.8111,-1775.7115"/>
<text text-anchor="middle" x="2493.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">fu_of_study_subject</text>
</g>
<!-- aliquot&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>aliquot&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M874.0952,-6413.3902C887.8957,-6285.0953 913.5821,-6124.1369 958.1493,-6075 977.1397,-6054.0625 1001.8742,-6079.3737 1019.1493,-6057 1051.6418,-6014.9178 1080.2846,-4658.9786 1093.8401,-3898.6149"/>
<polygon fill="#000000" stroke="#000000" points="1097.34,-3898.6421 1094.0187,-3888.5813 1090.3411,-3898.5174 1097.34,-3898.6421"/>
<text text-anchor="middle" x="1023.1493" y="-6078.8" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_of_sample</text>
</g>
<!-- aliquot&#45;&gt;analyte -->
<g id="edge17" class="edge">
<title>aliquot&#45;&gt;analyte</title>
<path fill="none" stroke="#000000" d="M717.4857,-6413.3278C705.3507,-6398.6403 693.1939,-6383.9264 681.3554,-6369.5977"/>
<polygon fill="#000000" stroke="#000000" points="683.881,-6367.1594 674.8134,-6361.6796 678.4846,-6371.618 683.881,-6367.1594"/>
<text text-anchor="middle" x="762.6493" y="-6383.8" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_of_analyte</text>
</g>
<!-- aliquot&#45;&gt;laboratory_procedure -->
<g id="edge8" class="edge">
<title>aliquot&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M859.7993,-6413.2719C858.219,-5633.4739 851.7677,-2450.0992 850.4035,-1776.9151"/>
<polygon fill="#000000" stroke="#000000" points="853.9032,-1776.7011 850.3828,-1766.7082 846.9032,-1776.7153 853.9032,-1776.7011"/>
<text text-anchor="middle" x="935.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_processed_by</text>
</g>
<!-- stratification_factor -->
<g id="node9" class="node">
<title>stratification_factor</title>
<path fill="none" stroke="#000000" d="M3469.1493,-3313.5C3469.1493,-3313.5 3931.1493,-3313.5 3931.1493,-3313.5 3937.1493,-3313.5 3943.1493,-3319.5 3943.1493,-3325.5 3943.1493,-3325.5 3943.1493,-3462.5 3943.1493,-3462.5 3943.1493,-3468.5 3937.1493,-3474.5 3931.1493,-3474.5 3931.1493,-3474.5 3469.1493,-3474.5 3469.1493,-3474.5 3463.1493,-3474.5 3457.1493,-3468.5 3457.1493,-3462.5 3457.1493,-3462.5 3457.1493,-3325.5 3457.1493,-3325.5 3457.1493,-3319.5 3463.1493,-3313.5 3469.1493,-3313.5"/>
<text text-anchor="middle" x="3537.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification_factor</text>
<polyline fill="none" stroke="#000000" points="3617.1493,-3313.5 3617.1493,-3474.5 "/>
<text text-anchor="middle" x="3627.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3638.1493,-3313.5 3638.1493,-3474.5 "/>
<text text-anchor="middle" x="3780.1493" y="-3459.3" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="3638.1493,-3451.5 3922.1493,-3451.5 "/>
<text text-anchor="middle" x="3780.1493" y="-3436.3" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="3638.1493,-3428.5 3922.1493,-3428.5 "/>
<text text-anchor="middle" x="3780.1493" y="-3413.3" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="3638.1493,-3405.5 3922.1493,-3405.5 "/>
<text text-anchor="middle" x="3780.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="3638.1493,-3382.5 3922.1493,-3382.5 "/>
<text text-anchor="middle" x="3780.1493" y="-3367.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification_code</text>
<polyline fill="none" stroke="#000000" points="3638.1493,-3359.5 3922.1493,-3359.5 "/>
<text text-anchor="middle" x="3780.1493" y="-3344.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification_factor_id</text>
<polyline fill="none" stroke="#000000" points="3638.1493,-3336.5 3922.1493,-3336.5 "/>
<text text-anchor="middle" x="3780.1493" y="-3321.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="3922.1493,-3313.5 3922.1493,-3474.5 "/>
<text text-anchor="middle" x="3932.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification_factor&#45;&gt;study_subject -->
<g id="edge26" class="edge">
<title>stratification_factor&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M3712.1334,-3313.0826C3743.4295,-3069.5035 3802.3279,-2333.8884 3448.1493,-1910 3380.7676,-1829.3561 3120.5883,-1749.024 2933.5195,-1699.8155"/>
<polygon fill="#000000" stroke="#000000" points="2934.3901,-1696.4255 2923.8296,-1697.2771 2932.6162,-1703.1971 2934.3901,-1696.4255"/>
<text text-anchor="middle" x="3494.1493" y="-1880.8" font-family="Times,serif" font-size="14.00" fill="#000000">sf_of_study_subject</text>
</g>
<!-- diagnosis&#45;&gt;study_subject -->
<g id="edge34" class="edge">
<title>diagnosis&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M2742.6617,-1910.4883C2742.1357,-1896.1672 2741.6261,-1882.2924 2741.1343,-1868.9027"/>
<polygon fill="#000000" stroke="#000000" points="2744.6265,-1868.6235 2740.7617,-1858.7587 2737.6312,-1868.8805 2744.6265,-1868.6235"/>
<text text-anchor="middle" x="2839.1493" y="-1880.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_of_study_subject</text>
</g>
<!-- analyte&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>analyte&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M669.7266,-6108.4803C672.5216,-6102.3873 675.0209,-6096.2157 677.1493,-6090 718.9536,-5967.9218 630.5049,-5034.2563 705.1493,-4929 742.2517,-4876.6818 799.2154,-4927.378 840.1493,-4878 1064.1706,-4607.7667 1125.3402,-4213.1716 1132.8243,-3898.7955"/>
<polygon fill="#000000" stroke="#000000" points="1136.3281,-3898.6576 1133.0493,-3888.5829 1129.3298,-3898.5033 1136.3281,-3898.6576"/>
<text text-anchor="middle" x="771.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_of_sample</text>
</g>
<!-- analyte&#45;&gt;laboratory_procedure -->
<g id="edge4" class="edge">
<title>analyte&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M415.0737,-6108.3498C402.7424,-6092.3279 392.0293,-6075.1404 384.1493,-6057 181.2053,-5589.8032 373.2605,-5420.3618 370.1493,-4911 361.9915,-3575.3998 -81.0304,-3098.6103 528.1493,-1910 555.3492,-1856.9286 598.8728,-1811.0526 645.2393,-1773.2996"/>
<polygon fill="#000000" stroke="#000000" points="647.6982,-1775.8143 653.3123,-1766.8292 643.3203,-1770.3522 647.6982,-1775.8143"/>
<text text-anchor="middle" x="449.1493" y="-4899.8" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_processed_by</text>
</g>
<!-- analyte&#45;&gt;fraction -->
<g id="edge37" class="edge">
<title>analyte&#45;&gt;fraction</title>
<path fill="none" stroke="#000000" d="M541.6454,-6108.3068C540.7028,-6102.1339 539.8607,-6096.0075 539.1493,-6090 516.5668,-5899.3014 518.8095,-5672.0393 521.7762,-5560.9452"/>
<polygon fill="#000000" stroke="#000000" points="525.2765,-5560.9782 522.0554,-5550.8849 518.2792,-5560.7839 525.2765,-5560.9782"/>
<text text-anchor="middle" x="608.1493" y="-6078.8" font-family="Times,serif" font-size="14.00" fill="#000000">analyte_of_fraction</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M1431.6493,-3152.5C1431.6493,-3152.5 1842.6493,-3152.5 1842.6493,-3152.5 1848.6493,-3152.5 1854.6493,-3158.5 1854.6493,-3164.5 1854.6493,-3164.5 1854.6493,-3623.5 1854.6493,-3623.5 1854.6493,-3629.5 1848.6493,-3635.5 1842.6493,-3635.5 1842.6493,-3635.5 1431.6493,-3635.5 1431.6493,-3635.5 1425.6493,-3635.5 1419.6493,-3629.5 1419.6493,-3623.5 1419.6493,-3623.5 1419.6493,-3164.5 1419.6493,-3164.5 1419.6493,-3158.5 1425.6493,-3152.5 1431.6493,-3152.5"/>
<text text-anchor="middle" x="1460.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="1501.6493,-3152.5 1501.6493,-3635.5 "/>
<text text-anchor="middle" x="1512.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3152.5 1522.6493,-3635.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3620.3" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3612.5 1833.6493,-3612.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3597.3" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3589.5 1833.6493,-3589.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3574.3" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3566.5 1833.6493,-3566.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3551.3" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3543.5 1833.6493,-3543.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3528.3" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3520.5 1833.6493,-3520.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3505.3" font-family="Times,serif" font-size="14.00" fill="#000000">bmi</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3497.5 1833.6493,-3497.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3482.3" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3474.5 1833.6493,-3474.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3459.3" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3451.5 1833.6493,-3451.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3436.3" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3428.5 1833.6493,-3428.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3413.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_node_id</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3405.5 1833.6493,-3405.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3382.5 1833.6493,-3382.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3367.3" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3359.5 1833.6493,-3359.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3344.3" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3336.5 1833.6493,-3336.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3321.3" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3313.5 1833.6493,-3313.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3298.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3290.5 1833.6493,-3290.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3275.3" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3267.5 1833.6493,-3267.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3252.3" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3244.5 1833.6493,-3244.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3229.3" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3221.5 1833.6493,-3221.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3206.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3198.5 1833.6493,-3198.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3183.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="1522.6493,-3175.5 1833.6493,-3175.5 "/>
<text text-anchor="middle" x="1678.1493" y="-3160.3" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="1833.6493,-3152.5 1833.6493,-3635.5 "/>
<text text-anchor="middle" x="1844.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;study_subject -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M1601.6202,-3152.1687C1568.5305,-2828.8001 1562.4869,-2256.2242 1864.1493,-1910 1951.7709,-1809.4349 2304.2478,-1728.7273 2532.4906,-1685.6609"/>
<polygon fill="#000000" stroke="#000000" points="2533.404,-1689.0507 2542.5863,-1683.7652 2532.1121,-1682.1709 2533.404,-1689.0507"/>
<text text-anchor="middle" x="1991.1493" y="-1880.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_of_study_subject</text>
</g>
<!-- cross_reference_database -->
<g id="node13" class="node">
<title>cross_reference_database</title>
<path fill="none" stroke="#000000" d="M2889.6493,-1047.5C2889.6493,-1047.5 3360.6493,-1047.5 3360.6493,-1047.5 3366.6493,-1047.5 3372.6493,-1053.5 3372.6493,-1059.5 3372.6493,-1059.5 3372.6493,-1104.5 3372.6493,-1104.5 3372.6493,-1110.5 3366.6493,-1116.5 3360.6493,-1116.5 3360.6493,-1116.5 2889.6493,-1116.5 2889.6493,-1116.5 2883.6493,-1116.5 2877.6493,-1110.5 2877.6493,-1104.5 2877.6493,-1104.5 2877.6493,-1059.5 2877.6493,-1059.5 2877.6493,-1053.5 2883.6493,-1047.5 2889.6493,-1047.5"/>
<text text-anchor="middle" x="2979.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">cross_reference_database</text>
<polyline fill="none" stroke="#000000" points="3080.6493,-1047.5 3080.6493,-1116.5 "/>
<text text-anchor="middle" x="3091.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3101.6493,-1047.5 3101.6493,-1116.5 "/>
<text text-anchor="middle" x="3226.6493" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cross_reference_database_id</text>
<polyline fill="none" stroke="#000000" points="3101.6493,-1093.5 3351.6493,-1093.5 "/>
<text text-anchor="middle" x="3226.6493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">cross_reference_database_name</text>
<polyline fill="none" stroke="#000000" points="3101.6493,-1070.5 3351.6493,-1070.5 "/>
<text text-anchor="middle" x="3226.6493" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">cross_reference_database_url</text>
<polyline fill="none" stroke="#000000" points="3351.6493,-1047.5 3351.6493,-1116.5 "/>
<text text-anchor="middle" x="3362.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- project -->
<g id="node14" class="node">
<title>project</title>
<path fill="none" stroke="#000000" d="M3402.6493,-771.5C3402.6493,-771.5 3689.6493,-771.5 3689.6493,-771.5 3695.6493,-771.5 3701.6493,-777.5 3701.6493,-783.5 3701.6493,-783.5 3701.6493,-1380.5 3701.6493,-1380.5 3701.6493,-1386.5 3695.6493,-1392.5 3689.6493,-1392.5 3689.6493,-1392.5 3402.6493,-1392.5 3402.6493,-1392.5 3396.6493,-1392.5 3390.6493,-1386.5 3390.6493,-1380.5 3390.6493,-1380.5 3390.6493,-783.5 3390.6493,-783.5 3390.6493,-777.5 3396.6493,-771.5 3402.6493,-771.5"/>
<text text-anchor="middle" x="3424.6493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">project</text>
<polyline fill="none" stroke="#000000" points="3458.6493,-771.5 3458.6493,-1392.5 "/>
<text text-anchor="middle" x="3469.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3479.6493,-771.5 3479.6493,-1392.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1377.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_type</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1369.5 3680.6493,-1369.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fraction</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1346.5 3680.6493,-1346.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1331.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_approval</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1323.5 3680.6493,-1323.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1308.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession_number</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1300.5 3680.6493,-1300.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1285.3" font-family="Times,serif" font-size="14.00" fill="#000000">embargo_date</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1277.5 3680.6493,-1277.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1262.3" font-family="Times,serif" font-size="14.00" fill="#000000">end_date</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1254.5 3680.6493,-1254.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1239.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_review</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1231.5 3680.6493,-1231.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1208.5 3680.6493,-1208.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">intended_release_date</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1185.5 3680.6493,-1185.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_legacy</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1162.5 3680.6493,-1162.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1139.5 3680.6493,-1139.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_acronym</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1116.5 3680.6493,-1116.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_external_url</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1093.5 3680.6493,-1093.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_full_description</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1070.5 3680.6493,-1070.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_id</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1047.5 3680.6493,-1047.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_manager</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1024.5 3680.6493,-1024.5 "/>
<text text-anchor="middle" x="3580.1493" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_name</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-1001.5 3680.6493,-1001.5 "/>
<text text-anchor="middle" x="3580.1493" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_short_description</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-978.5 3680.6493,-978.5 "/>
<text text-anchor="middle" x="3580.1493" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_sort_order</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-955.5 3680.6493,-955.5 "/>
<text text-anchor="middle" x="3580.1493" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">project_type</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-932.5 3680.6493,-932.5 "/>
<text text-anchor="middle" x="3580.1493" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">releasable</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-909.5 3680.6493,-909.5 "/>
<text text-anchor="middle" x="3580.1493" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_requested</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-886.5 3680.6493,-886.5 "/>
<text text-anchor="middle" x="3580.1493" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">released</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-863.5 3680.6493,-863.5 "/>
<text text-anchor="middle" x="3580.1493" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">request_submission</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-840.5 3680.6493,-840.5 "/>
<text text-anchor="middle" x="3580.1493" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_date</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-817.5 3680.6493,-817.5 "/>
<text text-anchor="middle" x="3580.1493" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">state</text>
<polyline fill="none" stroke="#000000" points="3479.6493,-794.5 3680.6493,-794.5 "/>
<text text-anchor="middle" x="3580.1493" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_enabled</text>
<polyline fill="none" stroke="#000000" points="3680.6493,-771.5 3680.6493,-1392.5 "/>
<text text-anchor="middle" x="3691.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- project&#45;&gt;program -->
<g id="edge16" class="edge">
<title>project&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M3546.1493,-771.2781C3546.1493,-757.489 3546.1493,-743.6655 3546.1493,-729.9072"/>
<polygon fill="#000000" stroke="#000000" points="3549.6494,-729.9019 3546.1493,-719.902 3542.6494,-729.902 3549.6494,-729.9019"/>
<text text-anchor="middle" x="3617.1493" y="-741.8" font-family="Times,serif" font-size="14.00" fill="#000000">project_of_program</text>
</g>
<!-- file -->
<g id="node15" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M2227.6493,-6810.5C2227.6493,-6810.5 2412.6493,-6810.5 2412.6493,-6810.5 2418.6493,-6810.5 2424.6493,-6816.5 2424.6493,-6822.5 2424.6493,-6822.5 2424.6493,-7005.5 2424.6493,-7005.5 2424.6493,-7011.5 2418.6493,-7017.5 2412.6493,-7017.5 2412.6493,-7017.5 2227.6493,-7017.5 2227.6493,-7017.5 2221.6493,-7017.5 2215.6493,-7011.5 2215.6493,-7005.5 2215.6493,-7005.5 2215.6493,-6822.5 2215.6493,-6822.5 2215.6493,-6816.5 2221.6493,-6810.5 2227.6493,-6810.5"/>
<text text-anchor="middle" x="2235.1493" y="-6910.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="2254.6493,-6810.5 2254.6493,-7017.5 "/>
<text text-anchor="middle" x="2265.1493" y="-6910.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6810.5 2275.6493,-7017.5 "/>
<text text-anchor="middle" x="2339.6493" y="-7002.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6994.5 2403.6493,-6994.5 "/>
<text text-anchor="middle" x="2339.6493" y="-6979.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_format</text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6971.5 2403.6493,-6971.5 "/>
<text text-anchor="middle" x="2339.6493" y="-6956.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6948.5 2403.6493,-6948.5 "/>
<text text-anchor="middle" x="2339.6493" y="-6933.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_location</text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6925.5 2403.6493,-6925.5 "/>
<text text-anchor="middle" x="2339.6493" y="-6910.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6902.5 2403.6493,-6902.5 "/>
<text text-anchor="middle" x="2339.6493" y="-6887.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6879.5 2403.6493,-6879.5 "/>
<text text-anchor="middle" x="2339.6493" y="-6864.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_status</text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6856.5 2403.6493,-6856.5 "/>
<text text-anchor="middle" x="2339.6493" y="-6841.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2275.6493,-6833.5 2403.6493,-6833.5 "/>
<text text-anchor="middle" x="2339.6493" y="-6818.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2403.6493,-6810.5 2403.6493,-7017.5 "/>
<text text-anchor="middle" x="2414.1493" y="-6910.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2424.8893,-6906.9779C2700.6738,-6887.7016 3441.7476,-6830.6051 3676.1493,-6759 3835.654,-6710.2745 4009.1493,-6752.781 4009.1493,-6586 4009.1493,-6586 4009.1493,-6586 4009.1493,-1651.5 4009.1493,-1569.5606 3995.3134,-1482.8571 3976.3408,-1402.4828"/>
<polygon fill="#000000" stroke="#000000" points="3979.734,-1401.6236 3974.0021,-1392.7132 3972.9264,-1403.2533 3979.734,-1401.6236"/>
<text text-anchor="middle" x="4054.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_study</text>
</g>
<!-- file&#45;&gt;program -->
<g id="edge10" class="edge">
<title>file&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2424.8956,-6909.9685C2726.2735,-6897.3427 3590.9383,-6853.635 3856.1493,-6759 3991.0852,-6710.8509 4128.1493,-6729.2691 4128.1493,-6586 4128.1493,-6586 4128.1493,-6586 4128.1493,-1082 4128.1493,-936.8081 4114.2124,-887.9352 4028.1493,-771 3948.5281,-662.8175 3823.7898,-576.4312 3721.1584,-517.9407"/>
<polygon fill="#000000" stroke="#000000" points="3722.6699,-514.7746 3712.2426,-512.8977 3719.2235,-520.8675 3722.6699,-514.7746"/>
<text text-anchor="middle" x="4184.6493" y="-4899.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_program</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2215.6365,-6911.9757C2000.0411,-6905.9776 1514.8607,-6882.5223 1380.1493,-6792 1292.7556,-6733.2738 1263.1493,-6691.2921 1263.1493,-6586 1263.1493,-6586 1263.1493,-6586 1263.1493,-5493 1263.1493,-4946.9097 1208.303,-4323.2368 1162.6337,-3898.5765"/>
<polygon fill="#000000" stroke="#000000" points="1166.1081,-3898.1497 1161.5567,-3888.5823 1159.1484,-3898.8998 1166.1081,-3898.1497"/>
<text text-anchor="middle" x="1314.6493" y="-6231.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_sample</text>
</g>
<!-- file&#45;&gt;aliquot -->
<g id="edge13" class="edge">
<title>file&#45;&gt;aliquot</title>
<path fill="none" stroke="#000000" d="M2215.2131,-6909.9411C1965.4967,-6899.1868 1342.3094,-6865.5958 1148.1493,-6792 1126.1722,-6783.6696 1104.3358,-6773.2328 1083.0884,-6761.5045"/>
<polygon fill="#000000" stroke="#000000" points="1084.7727,-6758.4363 1074.3408,-6756.5855 1081.3416,-6764.5378 1084.7727,-6758.4363"/>
<text text-anchor="middle" x="1198.6493" y="-6780.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_aliquot</text>
</g>
<!-- file&#45;&gt;diagnosis -->
<g id="edge2" class="edge">
<title>file&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M2424.9608,-6890.4523C2628.4334,-6841.6897 3057.1493,-6722.7246 3057.1493,-6586 3057.1493,-6586 3057.1493,-6586 3057.1493,-5493 3057.1493,-5242.1911 3064.2298,-5178.4492 3038.1493,-4929 3035.7559,-4906.1079 3032.9271,-4900.7048 3029.1493,-4878 3026.7368,-4863.5006 3024.3181,-4848.9202 3021.8946,-4834.2694"/>
<polygon fill="#000000" stroke="#000000" points="3025.3002,-4833.4107 3020.216,-4824.1155 3018.3939,-4834.5525 3025.3002,-4833.4107"/>
<text text-anchor="middle" x="3116.6493" y="-6231.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_diagnosis</text>
</g>
<!-- file&#45;&gt;project -->
<g id="edge31" class="edge">
<title>file&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M2424.8615,-6903.0304C2773.0591,-6865.163 3870.1493,-6734.1006 3870.1493,-6586 3870.1493,-6586 3870.1493,-6586 3870.1493,-6082.5 3870.1493,-5569.7956 3652.0825,-5386.177 3884.1493,-4929 3901.2488,-4895.3137 3935.2546,-4911.7895 3952.1493,-4878 4025.8899,-4730.5189 3969.3746,-2073.9867 3952.1493,-1910 3928.4642,-1684.5142 4012.5027,-1565.05 3846.1493,-1411 3801.7366,-1369.872 3760.8403,-1427.5661 3711.1493,-1393 3710.7573,-1392.7273 3710.3662,-1392.4534 3709.9759,-1392.1783"/>
<polygon fill="#000000" stroke="#000000" points="3712.03,-1389.3442 3701.9049,-1386.2242 3707.8744,-1394.9773 3712.03,-1389.3442"/>
<text text-anchor="middle" x="3935.6493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_project</text>
</g>
<!-- file&#45;&gt;laboratory_procedure -->
<g id="edge27" class="edge">
<title>file&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M2215.392,-6871.2015C2155.7228,-6844.0187 2081.4728,-6805.2687 2023.1493,-6759 1700.7021,-6503.1989 1568.8333,-6440.4073 1419.1493,-6057 1228.4754,-5568.599 1391.4454,-5402.1573 1379.1493,-4878 1377.1942,-4794.6548 1385.5747,-1946.9055 1340.1493,-1877 1285.3302,-1792.6383 1190.223,-1739.369 1098.2979,-1705.9531"/>
<polygon fill="#000000" stroke="#000000" points="1099.4345,-1702.6426 1088.8399,-1702.5801 1097.0831,-1709.2359 1099.4345,-1702.6426"/>
<text text-anchor="middle" x="1534.6493" y="-6078.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_laboratory_procedure</text>
</g>
<!-- file&#45;&gt;study_subject -->
<g id="edge22" class="edge">
<title>file&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M2254.7691,-6810.4742C2075.6489,-6519.9466 1579.2115,-5666.6725 1411.1493,-4878 1393.9666,-4797.366 1358.7437,-1973.6454 1411.1493,-1910 1550.8296,-1740.3618 2197.8507,-1680.4803 2532.0682,-1660.629"/>
<polygon fill="#000000" stroke="#000000" points="2532.5766,-1664.1052 2542.3541,-1660.0248 2532.1661,-1657.1173 2532.5766,-1664.1052"/>
<text text-anchor="middle" x="1930.6493" y="-6078.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_of_study_subject</text>
</g>
<!-- laboratory_procedure&#45;&gt;program -->
<g id="edge15" class="edge">
<title>laboratory_procedure&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1012.8372,-1536.3556C1279.4915,-1352.1451 1831.2117,-989.7173 2343.1493,-771 2694.4588,-620.9086 3131.5447,-516.9238 3370.2635,-466.6172"/>
<polygon fill="#000000" stroke="#000000" points="3371.0084,-470.0372 3380.0753,-464.5562 3369.5693,-463.1867 3371.0084,-470.0372"/>
<text text-anchor="middle" x="2466.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_procedure_of_program</text>
</g>
<!-- therapeutic_procedure -->
<g id="node17" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2577.6493,-5286C2577.6493,-5286 3016.6493,-5286 3016.6493,-5286 3022.6493,-5286 3028.6493,-5292 3028.6493,-5298 3028.6493,-5298 3028.6493,-5688 3028.6493,-5688 3028.6493,-5694 3022.6493,-5700 3016.6493,-5700 3016.6493,-5700 2577.6493,-5700 2577.6493,-5700 2571.6493,-5700 2565.6493,-5694 2565.6493,-5688 2565.6493,-5688 2565.6493,-5298 2565.6493,-5298 2565.6493,-5292 2571.6493,-5286 2577.6493,-5286"/>
<text text-anchor="middle" x="2656.1493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2746.6493,-5286 2746.6493,-5700 "/>
<text text-anchor="middle" x="2757.1493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5286 2767.6493,-5700 "/>
<text text-anchor="middle" x="2887.6493" y="-5684.8" font-family="Times,serif" font-size="14.00" fill="#000000">all_endocrine_therapy_stopped</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5677 3007.6493,-5677 "/>
<text text-anchor="middle" x="2887.6493" y="-5661.8" font-family="Times,serif" font-size="14.00" fill="#000000">chemotherapy_regimen</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5654 3007.6493,-5654 "/>
<text text-anchor="middle" x="2887.6493" y="-5638.8" font-family="Times,serif" font-size="14.00" fill="#000000">chemotherapy_regimen_group</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5631 3007.6493,-5631 "/>
<text text-anchor="middle" x="2887.6493" y="-5615.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5608 3007.6493,-5608 "/>
<text text-anchor="middle" x="2887.6493" y="-5592.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5585 3007.6493,-5585 "/>
<text text-anchor="middle" x="2887.6493" y="-5569.8" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_type</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5562 3007.6493,-5562 "/>
<text text-anchor="middle" x="2887.6493" y="-5546.8" font-family="Times,serif" font-size="14.00" fill="#000000">initial_disease_status</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5539 3007.6493,-5539 "/>
<text text-anchor="middle" x="2887.6493" y="-5523.8" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5516 3007.6493,-5516 "/>
<text text-anchor="middle" x="2887.6493" y="-5500.8" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5493 3007.6493,-5493 "/>
<text text-anchor="middle" x="2887.6493" y="-5477.8" font-family="Times,serif" font-size="14.00" fill="#000000">regimen_or_line_of_therapy</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5470 3007.6493,-5470 "/>
<text text-anchor="middle" x="2887.6493" y="-5454.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5447 3007.6493,-5447 "/>
<text text-anchor="middle" x="2887.6493" y="-5431.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5424 3007.6493,-5424 "/>
<text text-anchor="middle" x="2887.6493" y="-5408.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5401 3007.6493,-5401 "/>
<text text-anchor="middle" x="2887.6493" y="-5385.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_effect</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5378 3007.6493,-5378 "/>
<text text-anchor="middle" x="2887.6493" y="-5362.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_intent_type</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5355 3007.6493,-5355 "/>
<text text-anchor="middle" x="2887.6493" y="-5339.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_or_therapy</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5332 3007.6493,-5332 "/>
<text text-anchor="middle" x="2887.6493" y="-5316.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2767.6493,-5309 3007.6493,-5309 "/>
<text text-anchor="middle" x="2887.6493" y="-5293.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3007.6493,-5286 3007.6493,-5700 "/>
<text text-anchor="middle" x="3018.1493" y="-5489.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;diagnosis -->
<g id="edge3" class="edge">
<title>therapeutic_procedure&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M2797.1493,-5285.9953C2797.1493,-5180.5525 2797.1493,-5042.0863 2797.1493,-4887.9286"/>
<polygon fill="#000000" stroke="#000000" points="2800.6494,-4887.7519 2797.1493,-4877.752 2793.6494,-4887.752 2800.6494,-4887.7519"/>
<text text-anchor="middle" x="2853.1493" y="-4899.8" font-family="Times,serif" font-size="14.00" fill="#000000">tp_of_diagnosis</text>
</g>
<!-- fraction&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>fraction&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M507.9652,-5435.2937C478.592,-5316.7284 431.7217,-5044.4159 572.1493,-4896 612.8434,-4852.991 659.7192,-4917.1374 704.1493,-4878 979.0252,-4635.8685 1073.5245,-4226.4735 1102.0689,-3898.9431"/>
<polygon fill="#000000" stroke="#000000" points="1105.5723,-3899.0512 1102.935,-3888.7899 1098.5976,-3898.4562 1105.5723,-3899.0512"/>
<text text-anchor="middle" x="640.1493" y="-4899.8" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_of_sample</text>
</g>
<!-- fraction&#45;&gt;laboratory_procedure -->
<g id="edge21" class="edge">
<title>fraction&#45;&gt;laboratory_procedure</title>
<path fill="none" stroke="#000000" d="M524.6544,-5435.4842C528.7073,-5002.2297 558.8225,-2258.2443 674.1493,-1910 689.918,-1862.3845 717.2267,-1815.4704 745.6927,-1774.9526"/>
<polygon fill="#000000" stroke="#000000" points="748.6401,-1776.8474 751.5892,-1766.6713 742.9378,-1772.7873 748.6401,-1776.8474"/>
<text text-anchor="middle" x="755.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">fraction_processed_by</text>
</g>
<!-- family_medical_history -->
<g id="node19" class="node">
<title>family_medical_history</title>
<path fill="none" stroke="#000000" d="M1885.1493,-3313.5C1885.1493,-3313.5 2365.1493,-3313.5 2365.1493,-3313.5 2371.1493,-3313.5 2377.1493,-3319.5 2377.1493,-3325.5 2377.1493,-3325.5 2377.1493,-3462.5 2377.1493,-3462.5 2377.1493,-3468.5 2371.1493,-3474.5 2365.1493,-3474.5 2365.1493,-3474.5 1885.1493,-3474.5 1885.1493,-3474.5 1879.1493,-3474.5 1873.1493,-3468.5 1873.1493,-3462.5 1873.1493,-3462.5 1873.1493,-3325.5 1873.1493,-3325.5 1873.1493,-3319.5 1879.1493,-3313.5 1885.1493,-3313.5"/>
<text text-anchor="middle" x="1964.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_medical_history</text>
<polyline fill="none" stroke="#000000" points="2055.1493,-3313.5 2055.1493,-3474.5 "/>
<text text-anchor="middle" x="2065.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2076.1493,-3313.5 2076.1493,-3474.5 "/>
<text text-anchor="middle" x="2216.1493" y="-3459.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_history_id</text>
<polyline fill="none" stroke="#000000" points="2076.1493,-3451.5 2356.1493,-3451.5 "/>
<text text-anchor="middle" x="2216.1493" y="-3436.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship_age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2076.1493,-3428.5 2356.1493,-3428.5 "/>
<text text-anchor="middle" x="2216.1493" y="-3413.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship_gender</text>
<polyline fill="none" stroke="#000000" points="2076.1493,-3405.5 2356.1493,-3405.5 "/>
<text text-anchor="middle" x="2216.1493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship_primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2076.1493,-3382.5 2356.1493,-3382.5 "/>
<text text-anchor="middle" x="2216.1493" y="-3367.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship_type</text>
<polyline fill="none" stroke="#000000" points="2076.1493,-3359.5 2356.1493,-3359.5 "/>
<text text-anchor="middle" x="2216.1493" y="-3344.3" font-family="Times,serif" font-size="14.00" fill="#000000">relative_with_cancer_history</text>
<polyline fill="none" stroke="#000000" points="2076.1493,-3336.5 2356.1493,-3336.5 "/>
<text text-anchor="middle" x="2216.1493" y="-3321.3" font-family="Times,serif" font-size="14.00" fill="#000000">relatives_with_cancer_history_count</text>
<polyline fill="none" stroke="#000000" points="2356.1493,-3313.5 2356.1493,-3474.5 "/>
<text text-anchor="middle" x="2366.6493" y="-3390.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_medical_history&#45;&gt;study_subject -->
<g id="edge32" class="edge">
<title>family_medical_history&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M2105.3786,-3313.1108C2050.9399,-3070.0549 1923.1117,-2334.8191 2242.1493,-1877 2309.4333,-1780.4475 2428.693,-1724.3719 2532.8251,-1692.289"/>
<polygon fill="#000000" stroke="#000000" points="2533.9725,-1695.5987 2542.5314,-1689.354 2531.9463,-1688.8983 2533.9725,-1695.5987"/>
<text text-anchor="middle" x="2320.6493" y="-1880.8" font-family="Times,serif" font-size="14.00" fill="#000000">fmh_of_study_subject</text>
</g>
<!-- study_subject&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_subject&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2923.7015,-1620.1881C3172.5722,-1576.1297 3590.7648,-1490.2651 3711.1493,-1393 3711.326,-1392.8573 3711.5025,-1392.7143 3711.6788,-1392.5711"/>
<polygon fill="#000000" stroke="#000000" points="3714.1175,-1395.0924 3719.4921,-1385.962 3709.5968,-1389.7479 3714.1175,-1395.0924"/>
<text text-anchor="middle" x="3757.6493" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_of_study</text>
</g>
<!-- study_subject&#45;&gt;program -->
<g id="edge24" class="edge">
<title>study_subject&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2653.3435,-1444.1877C2594.0372,-1252.5715 2544.3292,-968.4748 2679.1493,-771 2759.4974,-653.3119 3140.5397,-536.9055 3369.8933,-475.8575"/>
<polygon fill="#000000" stroke="#000000" points="3370.9126,-479.2083 3379.681,-473.2614 3369.1179,-472.4422 3370.9126,-479.2083"/>
<text text-anchor="middle" x="2774.1493" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_of_program</text>
</g>
<!-- study_subject&#45;&gt;cross_reference_database -->
<g id="edge38" class="edge">
<title>study_subject&#45;&gt;cross_reference_database</title>
<path fill="none" stroke="#000000" d="M2875.7792,-1444.2864C2955.9734,-1327.7799 3049.0708,-1192.5274 3095.5533,-1124.9972"/>
<polygon fill="#000000" stroke="#000000" points="3098.4701,-1126.9326 3101.257,-1116.7109 3092.7041,-1122.9637 3098.4701,-1126.9326"/>
<text text-anchor="middle" x="3019.6493" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_cross_referenced_at</text>
</g>
<!-- study_subject&#45;&gt;project -->
<g id="edge29" class="edge">
<title>study_subject&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M2924.0118,-1613.0252C3064.4729,-1576.4918 3252.7244,-1509.3581 3382.1493,-1393 3382.504,-1392.6812 3382.858,-1392.3614 3383.2113,-1392.0407"/>
<polygon fill="#000000" stroke="#000000" points="3385.6377,-1394.5635 3390.5384,-1385.1702 3380.8496,-1389.4572 3385.6377,-1394.5635"/>
<text text-anchor="middle" x="3443.1493" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject_of_project</text>
</g>
</g>
</svg>
</div>