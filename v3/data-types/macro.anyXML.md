---
layout: sidebar
sidebar: s1
version: "v3"
title: "macro.anyXML"

---

<div class="macroSpec">
   <h3 id="macro.anyXML">macro.anyXML</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">macro.anyXML</span> Permits any XML elements except those from the MEI or SVG namespace.
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
            <span class="label" lang="en">Used by</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="/{{ page.version }}/extMeta">extMeta</a>
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
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:element&gt;</span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:anyName&gt;</span>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:except&gt;</span>
                           
                           <div class="indent5">
                              <span data-indentation="5" class="element">&lt;rng:nsName/&gt;</span>
                           </div>
                           
                           <div class="indent5">
                              <span data-indentation="5" class="element">&lt;rng:nsName/&gt;</span>
                           </div>
                           
                           <span data-indentation="4" class="element">&lt;/rng:except&gt;</span>
                        </div>
                        
                        <span data-indentation="3" class="element">&lt;/rng:anyName&gt;</span>
                     </div>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:zeroOrMore&gt;</span>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:attribute&gt;</span>
                           
                           <div class="indent5">
                              <span data-indentation="5" class="element">&lt;rng:anyName/&gt;</span>
                           </div>
                           
                           <span data-indentation="4" class="element">&lt;/rng:attribute&gt;</span>
                        </div>
                        
                        <span data-indentation="3" class="element">&lt;/rng:zeroOrMore&gt;</span>
                     </div>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:zeroOrMore&gt;</span>
                        
                        <div class="indent4">
                           <span data-indentation="4" class="element">&lt;rng:choice&gt;</span>
                           
                           <div class="indent5">
                              <span data-indentation="5" class="element">&lt;rng:text/&gt;</span>
                           </div>
                           
                           <div class="indent5">
                              <span data-indentation="5" class="element">&lt;rng:ref 
                                 <span class="attribute">name=</span>
                                 <span class="attributevalue">"
                                    <a class="link_odd" href="/macro.anyXML">macro.anyXML</a>"
                                 </span>/&gt;
                              </span>
                           </div>
                           
                           <span data-indentation="4" class="element">&lt;/rng:choice&gt;</span>
                        </div>
                        
                        <span data-indentation="3" class="element">&lt;/rng:zeroOrMore&gt;</span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/rng:element&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>