---
layout: sidebar
sidebar: s1
version: "v3"
title: "att.canonical"

---

<div class="classSpec att">
   <h3 id="att.canonical">att.canonical</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">att.canonical</span> Attributes that can be used to associate a representation such as a name or title
            with
            canonical information about the object being named or referenced.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI.shared</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Members</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/perfRes">perfRes</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/perfResList">perfResList</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/resp">resp</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/title">title</a> (direct members of att.canonical)
               </div>
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/addName">addName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/bloc">bloc</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/corpName">corpName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/country">country</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/district">district</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/famName">famName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/foreName">foreName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/genName">genName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/geogFeat">geogFeat</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/geogName">geogName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/name">name</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/nameLink">nameLink</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/periodName">periodName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/persName">persName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/region">region</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/repository">repository</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/roleName">roleName</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/settlement">settlement</a>, 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/styleName">styleName</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.name">att.name</a>)
                  </span>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Attributes</span>
         </td>
         <td class="wovenodd-col2">
            <div class="attributeDef">
               <span class="attribute">@codedval</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">a value that represents or identifies the element content. May serve as a primary
                  key in a web-accessible database identified by the authURI attribute.
               </span>
               One or more values of datatype 
               <span style="font-weight: 500;">NMTOKEN</span>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.canonical">att.canonical</a>
               </span>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Declaration</span>
         </td>
         <td class="wovenodd-col2">
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;attDef 
                     <span class="attribute">ident=</span>
                     <span class="attributevalue">"codedval"</span> 
                     <span class="attribute">usage=</span>
                     <span class="attributevalue">"opt"</span>&gt;
                  </span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;desc&gt;</span>a value that represents or identifies the element content. May serve as a primary
                     key in a web-accessible database identified by the authURI attribute.
                     <span data-indentation="2" class="element">&lt;/desc&gt;</span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;datatype 
                        <span class="attribute">maxOccurs=</span>
                        <span class="attributevalue">"unbounded"</span> 
                        <span class="attribute">minOccurs=</span>
                        <span class="attributevalue">"1"</span>&gt;
                     </span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:data 
                           <span class="attribute">type=</span>
                           <span class="attributevalue">"NMTOKEN"</span>/&gt;
                        </span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/datatype&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/attDef&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>