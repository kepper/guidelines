---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.phrase.vis.cmn"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.phrase.vis.cmn">att.phrase.vis.cmn</h3>
      <div class="specs">
         <div class="desc">Visual domain attributes.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.cmn</div>
         </div>
         <div class="facet attributes" id="attributes">
            <div class="label">Attributes</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="attributes_compact_tab" href="#attributes" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="full" id="attributes_full_tab" href="#attributes" class="displayTab">full definition</a></li>
                  <li class="tab-item"><a data-display="class" id="attributes_class_tab" href="#attributes" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="attributes_module_tab" href="#attributes" class="displayTab">by module</a></li>
               </ul>
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Records the placement of Bezier control points as a series of pairs of space-separated values; e.g., 19 45 -32 118.">bezier</span>, <span class="ident attribute" title="Describes a curve as one or more pairs of values with respect to an imaginary line connecting the starting and ending points of the curve. The first value captures a distance to the left (positive value) or right (negative value) of the line, expressed in virtual units. The second value of each pair represents a point along the line, expressed as a percentage of the line's length. N.B. An MEI virtual unit (VU) is half the distance between adjacent staff lines.">bulge</span>, <span class="ident attribute" title="Describes a curve with a generic term indicating the direction of curvature.">curvedir</span>, <span class="ident attribute" title="Describes the line style of a curve.">lform</span>, <span class="ident attribute" title="Width of a curved line.">lwidth</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the placement of Bezier control points as a series of pairs of space-separated values; e.g., 19 45 -32 118.">bezier</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the placement of Bezier control points as a series of pairs of space-separated
                        values; e.g., 19 45 -32 118.</span><span class="attributeValues">
                        One or more values, each consisting of a sequence of <span style="font-weight: 500;">decimal</span> and <span style="font-weight: 500;">decimal</span> sub-values.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes a curve as one or more pairs of values with respect to an imaginary line connecting the starting and ending points of the curve. The first value captures a distance to the left (positive value) or right (negative value) of the line, expressed in virtual units. The second value of each pair represents a point along the line, expressed as a percentage of the line's length. N.B. An MEI virtual unit (VU) is half the distance between adjacent staff lines.">bulge</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes a curve as one or more pairs of values with respect to an imaginary line
                        connecting the starting and ending points of the curve. The first value captures a
                        distance to the left (positive value) or right (negative value) of the line, expressed
                        in
                        virtual units. The second value of each pair represents a point along the line, expressed
                        as a percentage of the line's length. N.B. An MEI virtual unit (VU) is half the distance
                        between adjacent staff lines.</span><span class="attributeValues">
                        One or more of <span style="font-weight: 500;">decimal</span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes a curve with a generic term indicating the direction of curvature.">curvedir</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes a curve with a generic term indicating the direction of curvature.</span><span class="attributeValues">
                        Allowed values are:
                        "<span style="font-weight: 500;">above</span>" <i>(Upward curve.)</i>,  "<span style="font-weight: 500;">below</span>" <i>(Downward curve.)</i>,  "<span style="font-weight: 500;">mixed</span>" <i>(A "meandering" curve, both above and below the items it pertains to.)</i></span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the line style of a curve.">lform</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the line style of a curve.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.lineform.html">data.LINEFORM</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Width of a curved line.">lwidth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Width of a curved line.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linewidth.html">data.LINEWIDTH</a>.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.curvature">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.curvature.html">att.curvature</a></label><span class="classDesc">(MEI.shared) Attributes that describe curvature.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the placement of Bezier control points as a series of pairs of space-separated values; e.g., 19 45 -32 118.">bezier</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the placement of Bezier control points as a series of pairs of space-separated
                              values; e.g., 19 45 -32 118.</span><span class="attributeValues">
                              One or more values, each consisting of a sequence of <span style="font-weight: 500;">decimal</span> and <span style="font-weight: 500;">decimal</span> sub-values.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes a curve as one or more pairs of values with respect to an imaginary line connecting the starting and ending points of the curve. The first value captures a distance to the left (positive value) or right (negative value) of the line, expressed in virtual units. The second value of each pair represents a point along the line, expressed as a percentage of the line's length. N.B. An MEI virtual unit (VU) is half the distance between adjacent staff lines.">bulge</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes a curve as one or more pairs of values with respect to an imaginary line
                              connecting the starting and ending points of the curve. The first value captures a
                              distance to the left (positive value) or right (negative value) of the line, expressed
                              in
                              virtual units. The second value of each pair represents a point along the line, expressed
                              as a percentage of the line's length. N.B. An MEI virtual unit (VU) is half the distance
                              between adjacent staff lines.</span><span class="attributeValues">
                              One or more of <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes a curve with a generic term indicating the direction of curvature.">curvedir</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes a curve with a generic term indicating the direction of curvature.</span><span class="attributeValues">
                              Allowed values are:
                              "<span style="font-weight: 500;">above</span>" <i>(Upward curve.)</i>,  "<span style="font-weight: 500;">below</span>" <i>(Downward curve.)</i>,  "<span style="font-weight: 500;">mixed</span>" <i>(A "meandering" curve, both above and below the items it pertains to.)</i></span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.curveRend">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.curverend.html">att.curveRend</a></label><span class="classDesc">(MEI.shared) Attributes that record the visual rendition of curves.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the line style of a curve.">lform</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the line style of a curve.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.lineform.html">data.LINEFORM</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Width of a curved line.">lwidth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Width of a curved line.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linewidth.html">data.LINEWIDTH</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc">Component declarations that are shared between two or more modules.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the placement of Bezier control points as a series of pairs of space-separated values; e.g., 19 45 -32 118.">bezier</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the placement of Bezier control points as a series of pairs of space-separated
                              values; e.g., 19 45 -32 118.</span><span class="attributeValues">
                              One or more values, each consisting of a sequence of <span style="font-weight: 500;">decimal</span> and <span style="font-weight: 500;">decimal</span> sub-values.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes a curve as one or more pairs of values with respect to an imaginary line connecting the starting and ending points of the curve. The first value captures a distance to the left (positive value) or right (negative value) of the line, expressed in virtual units. The second value of each pair represents a point along the line, expressed as a percentage of the line's length. N.B. An MEI virtual unit (VU) is half the distance between adjacent staff lines.">bulge</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes a curve as one or more pairs of values with respect to an imaginary line
                              connecting the starting and ending points of the curve. The first value captures a
                              distance to the left (positive value) or right (negative value) of the line, expressed
                              in
                              virtual units. The second value of each pair represents a point along the line, expressed
                              as a percentage of the line's length. N.B. An MEI virtual unit (VU) is half the distance
                              between adjacent staff lines.</span><span class="attributeValues">
                              One or more of <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes a curve with a generic term indicating the direction of curvature.">curvedir</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes a curve with a generic term indicating the direction of curvature.</span><span class="attributeValues">
                              Allowed values are:
                              "<span style="font-weight: 500;">above</span>" <i>(Upward curve.)</i>,  "<span style="font-weight: 500;">below</span>" <i>(Downward curve.)</i>,  "<span style="font-weight: 500;">mixed</span>" <i>(A "meandering" curve, both above and below the items it pertains to.)</i></span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the line style of a curve.">lform</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the line style of a curve.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.lineform.html">data.LINEFORM</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Width of a curved line.">lwidth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Width of a curved line.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linewidth.html">data.LINEWIDTH</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet availableAt" id="availableAt">
            <div class="label">Available at</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="availableAt_compact_tab" href="#availableAt" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="class" id="availableAt_class_tab" href="#availableAt" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="availableAt_module_tab" href="#availableAt" class="displayTab">by module</a></li>
               </ul>
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="Indication of 1) a &#34;unified melodic idea&#34; or 2) performance technique."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/phrase.html">phrase</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.phrase.vis.cmn">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.phrase.vis.cmn.html">att.phrase.vis.cmn</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="classBox" title="att.phrase.vis">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.phrase.vis.html">att.phrase.vis</a></label><span class="classDesc"></span></div>
                           <div class="classContent">
                              <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/phrase.html">phrase</a><span class="elementDesc">Indication of 1) a "unified melodic idea" or 2) performance technique.</span></div>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/phrase.html">phrase</a><span class="elementDesc">Indication of 1) a "unified melodic idea" or 2) performance technique.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.phrase.vis.cmn"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.cmn"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Visual domain attributes.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;classes&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.curvature.html">att.curvature</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.curverend.html">att.curveRend</a>"</span></span>/&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/classes&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/classSpec&gt;</span></div></code></div>
            </div>
         </div>
      </div><script type="text/javascript">
            
            var tabbedFacets = document.querySelectorAll('.facet ul.tab');
            
            var tabClick = function(e) {
                var style = e.target.getAttribute('data-display');
                var facetId = e.target.parentNode.parentNode.parentNode.parentNode.id;
                setTabs(facetId,style)
            }
            
            for(var facetUl of tabbedFacets) {
                var facetElem = facetUl.parentNode.parentNode;
                var facetId = facetElem.id;
                var storageName = 'meiSpecs_' + facetId + '_display';
                var defaultValue = facetUl.children[0].children[0].getAttribute('data-display');
                
                if(localStorage.getItem(storageName) === null) {
                    setTabs(facetElem.id,defaultValue);
                } else {
                    setTabs(facetElem.id,localStorage.getItem(storageName));
                }
                
                var tabs = facetUl.querySelectorAll('.tab-item a');
                
                for(var tab of tabs) {
                    tab.addEventListener('click',tabClick);
                }
                
            }
            
            function setTabs(facetId,style) {
                
                var storageName = 'meiSpecs_' + facetId + '_display';
                localStorage.setItem(storageName,style);
                
                var facetElem = document.getElementById(facetId);
                
                var oldTab = facetElem.querySelector('.displayTab.active');
                oldTab.classList.remove('active');
                
                var newTab = document.getElementById(facetId + '_' + style + '_tab');
                newTab.classList.add('active');
                
                var oldBox = facetElem.querySelector('.active.facetTabbedContent');
                oldBox.classList.remove('active');
                oldBox.style.display = 'none';
                
                var newBox = document.getElementById(facetId + '_tabbedContent_' + style);
                newBox.classList.add('active');
                newBox.style.display = 'block';
                
            }
        </script></div>
</div>