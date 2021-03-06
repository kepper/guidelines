---
layout: sidebar
sidebar: s1
version: "dev"
title: "data.ARTICULATION"
---
<div class="specPage">
   <div class="datatypeSpec">
      <h3 id="data.ARTICULATION">data.ARTICULATION</h3>
      <div class="specs">
         <div class="desc">The following list of articulations mostly corresponds to symbols from the Western
            Musical
            Symbols portion of the Unicode Standard. The dot and stroke values may be used in
            cases where
            interpretation is difficult or undesirable.
         </div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI</div>
         </div>
         <div class="facet usedBy" id="usedBy">
            <div class="label">Used by</div>
            <div class="statement list">
               <div class="classBox dtBox" title="Attribute Classes">
                  <div class="classHeading"><label class="classLabel">Attribute Classes</label><span class="classDesc">These class-based attributes use data.ARTICULATION</span></div>
                  <div class="classContent"><span class="ident attclass" data-ident="att.articulation.gestural" data-module="MEI.gestural"><a class="classLink" title="Attributes describing the method of performance." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.articulation.gestural.html">att.articulation.gestural</a>/<span title="Records performed articulation that differs from the written value.">@artic.ges</span></span><span class="ident attclass" data-ident="att.articulation" data-module="MEI.shared"><a class="classLink" title="Attributes for capturing the written signs that describe the method of performance." href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.articulation.html">att.articulation</a>/<span title="Encodes the written articulation(s). Articulations are normally encoded in order from the note head outward; that is, away from the stem. See additional notes at att.vis.note. Only articulations should be encoded in the artic attribute; for example, fingerings should be encoded using the fing element.">@artic</span></span></div>
               </div>
            </div>
         </div>
         <div class="facet allowedValues" id="allowedValues">
            <div class="label">Allowed Values</div>
            <div class="statement list">
               <div class="dataValueBox" id="acc"><span class="dataValue ident">acc</span><span class="dataValue desc">Accent (Unicode 1D17B).</span></div>
               <div class="dataValueBox" id="stacc"><span class="dataValue ident">stacc</span><span class="dataValue desc">Staccato (Unicode 1D17C).</span></div>
               <div class="dataValueBox" id="ten"><span class="dataValue ident">ten</span><span class="dataValue desc">Tenuto (Unicode 1D17D).</span></div>
               <div class="dataValueBox" id="stacciss"><span class="dataValue ident">stacciss</span><span class="dataValue desc">Staccatissimo (Unicode 1D17E).</span></div>
               <div class="dataValueBox" id="marc"><span class="dataValue ident">marc</span><span class="dataValue desc">Marcato (Unicode 1D17F).</span></div>
               <div class="dataValueBox" id="spicc"><span class="dataValue ident">spicc</span><span class="dataValue desc">Spiccato.</span></div>
               <div class="dataValueBox" id="doit"><span class="dataValue ident">doit</span><span class="dataValue desc">Main note followed by short slide to higher, indeterminate pitch (Unicode
                     1D185).</span></div>
               <div class="dataValueBox" id="scoop"><span class="dataValue ident">scoop</span><span class="dataValue desc">Main note preceded by short slide from lower, indeterminate pitch (Unicode
                     1D186).</span></div>
               <div class="dataValueBox" id="rip"><span class="dataValue ident">rip</span><span class="dataValue desc">Main note preceded by long slide from lower, often indeterminate pitch; also known
                     as "squeeze".</span></div>
               <div class="dataValueBox" id="plop"><span class="dataValue ident">plop</span><span class="dataValue desc">Main note preceded by "slide" from higher, indeterminate pitch.</span></div>
               <div class="dataValueBox" id="fall"><span class="dataValue ident">fall</span><span class="dataValue desc">Main note followed by short "slide" to lower, indeterminate pitch.</span></div>
               <div class="dataValueBox" id="longfall"><span class="dataValue ident">longfall</span><span class="dataValue desc">Main note followed by long "slide" to lower, indeterminate pitch.</span></div>
               <div class="dataValueBox" id="bend"><span class="dataValue ident">bend</span><span class="dataValue desc">"lip slur" to lower pitch, then return to written pitch.</span></div>
               <div class="dataValueBox" id="flip"><span class="dataValue ident">flip</span><span class="dataValue desc">Main note followed by quick upward rise, then descent in pitch (Unicode
                     1D187).</span></div>
               <div class="dataValueBox" id="smear"><span class="dataValue ident">smear</span><span class="dataValue desc">(Unicode 1D188).</span></div>
               <div class="dataValueBox" id="shake"><span class="dataValue ident">shake</span><span class="dataValue desc">Alternation between written pitch and next highest overtone (brass instruments) or
                     note minor third higher (woodwinds).</span></div>
               <div class="dataValueBox" id="dnbow"><span class="dataValue ident">dnbow</span><span class="dataValue desc">Down bow (Unicode 1D1AA).</span></div>
               <div class="dataValueBox" id="upbow"><span class="dataValue ident">upbow</span><span class="dataValue desc">Up bow (Unicode 1D1AB).</span></div>
               <div class="dataValueBox" id="harm"><span class="dataValue ident">harm</span><span class="dataValue desc">Harmonic (Unicode 1D1AC).</span></div>
               <div class="dataValueBox" id="snap"><span class="dataValue ident">snap</span><span class="dataValue desc">Snap pizzicato (Unicode 1D1AD).</span></div>
               <div class="dataValueBox" id="fingernail"><span class="dataValue ident">fingernail</span><span class="dataValue desc">Fingernail (Unicode 1D1B3).</span></div>
               <div class="dataValueBox" id="damp"><span class="dataValue ident">damp</span><span class="dataValue desc">Stop harp string from sounding (Unicode 1D1B4).</span></div>
               <div class="dataValueBox" id="dampall"><span class="dataValue ident">dampall</span><span class="dataValue desc">Stop all harp strings from sounding (Unicode 1D1B5).</span></div>
               <div class="dataValueBox" id="open"><span class="dataValue ident">open</span><span class="dataValue desc">Full (as opposed to stopped) tone.</span></div>
               <div class="dataValueBox" id="stop"><span class="dataValue ident">stop</span><span class="dataValue desc">"muffled" tone.</span></div>
               <div class="dataValueBox" id="dbltongue"><span class="dataValue ident">dbltongue</span><span class="dataValue desc">Double tongue (Unicode 1D18A).</span></div>
               <div class="dataValueBox" id="trpltongue"><span class="dataValue ident">trpltongue</span><span class="dataValue desc">Triple tongue (Unicode 1D18B).</span></div>
               <div class="dataValueBox" id="heel"><span class="dataValue ident">heel</span><span class="dataValue desc">Use heel (organ pedal).</span></div>
               <div class="dataValueBox" id="toe"><span class="dataValue ident">toe</span><span class="dataValue desc">Use toe (organ pedal).</span></div>
               <div class="dataValueBox" id="tap"><span class="dataValue ident">tap</span><span class="dataValue desc">Percussive effect on guitar string(s).</span></div>
               <div class="dataValueBox" id="lhpizz"><span class="dataValue ident">lhpizz</span><span class="dataValue desc">Left-hand pizzicato.</span></div>
               <div class="dataValueBox" id="dot"><span class="dataValue ident">dot</span><span class="dataValue desc">Uninterpreted dot.</span></div>
               <div class="dataValueBox" id="stroke"><span class="dataValue ident">stroke</span><span class="dataValue desc">Uninterpreted stroke.</span></div>
            </div>
         </div>
         <div class="facet constraints" id="constraints">
            <div class="label">Constraints</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="text" id="constraints_text_tab" href="#constraints" class="displayTab active">text</a></li>
                  <li class="tab-item"><a data-display="schematron" id="constraints_schematron_tab" href="#constraints" class="displayTab">schematron</a></li>
               </ul>
               <div id="constraints_tabbedContent_text" class="facetTabbedContent text active">
                  <div class="constraint">
                     <div class="schematronText">" " contains a deprecated value.</div>
                     <div class="schematronText">" " contains a deprecated value.</div>
                  </div>
               </div>
               <div id="constraints_tabbedContent_schematron" class="facetTabbedContent schematron">
                  <div class="constraint">
                     <div class="code" xml:space="preserve" data-lang="Schematron"><code>
                           <div class="indent1 indent"><span data-indentation="1" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"@artic"</span>&gt;</span>
                              
                              <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"not(contains(., 'marc-stacc')) and not(contains(., 'ten-stacc'))"</span>&gt;</span>"
                                 <div class="indent3 indent"><span data-indentation="3" class="element">&lt;sch:value-of <span class="attribute">select=</span><span class="attributevalue">"."</span>/&gt;</span></div>" contains a deprecated value.<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                              <span data-indentation="1" class="element">&lt;/sch:rule&gt;</span></div>
                           <div class="indent1 indent"><span data-indentation="1" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"@artic.ges"</span>&gt;</span>
                              
                              <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"not(contains(., 'marc-stacc')) and not(contains(., 'ten-stacc'))"</span>&gt;</span>"
                                 <div class="indent3 indent"><span data-indentation="3" class="element">&lt;sch:value-of <span class="attribute">select=</span><span class="attributevalue">"."</span>/&gt;</span></div>" contains a deprecated value.<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                              <span data-indentation="1" class="element">&lt;/sch:rule&gt;</span></div></code></div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;macroSpec <span class="attribute">ident=</span><span class="attributevalue">"data.ARTICULATION"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI"</span> <span class="attribute">type=</span><span class="attributevalue">"dt"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>The following list of articulations mostly corresponds to symbols from the Western
                           Musical
                           Symbols portion of the Unicode Standard. The dot and stroke values may be used in
                           cases where
                           interpretation is difficult or undesirable.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;content&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;valList <span class="attribute">type=</span><span class="attributevalue">"closed"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"acc"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Accent (Unicode 1D17B).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"stacc"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Staccato (Unicode 1D17C).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"ten"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Tenuto (Unicode 1D17D).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"stacciss"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Staccatissimo (Unicode 1D17E).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"marc"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Marcato (Unicode 1D17F).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"spicc"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Spiccato.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"doit"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Main note followed by short slide to higher, indeterminate pitch (Unicode
                                    1D185).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"scoop"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Main note preceded by short slide from lower, indeterminate pitch (Unicode
                                    1D186).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"rip"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Main note preceded by long slide from lower, often indeterminate pitch; also known
                                    as "squeeze".<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"plop"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Main note preceded by "slide" from higher, indeterminate pitch.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"fall"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Main note followed by short "slide" to lower, indeterminate pitch.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"longfall"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Main note followed by long "slide" to lower, indeterminate pitch.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"bend"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>"lip slur" to lower pitch, then return to written pitch.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"flip"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Main note followed by quick upward rise, then descent in pitch (Unicode
                                    1D187).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"smear"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>(Unicode 1D188).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"shake"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Alternation between written pitch and next highest overtone (brass instruments) or
                                    note minor third higher (woodwinds).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"dnbow"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Down bow (Unicode 1D1AA).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"upbow"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Up bow (Unicode 1D1AB).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"harm"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Harmonic (Unicode 1D1AC).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"snap"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Snap pizzicato (Unicode 1D1AD).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"fingernail"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Fingernail (Unicode 1D1B3).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"damp"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Stop harp string from sounding (Unicode 1D1B4).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"dampall"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Stop all harp strings from sounding (Unicode 1D1B5).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"open"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Full (as opposed to stopped) tone.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"stop"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>"muffled" tone.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"dbltongue"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Double tongue (Unicode 1D18A).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"trpltongue"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Triple tongue (Unicode 1D18B).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"heel"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Use heel (organ pedal).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"toe"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Use toe (organ pedal).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"tap"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Percussive effect on guitar string(s).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"lhpizz"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Left-hand pizzicato.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"dot"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Uninterpreted dot.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"stroke"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Uninterpreted stroke.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/valList&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/content&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;constraintSpec <span class="attribute">ident=</span><span class="attributevalue">"warn_deprecated"</span> <span class="attribute">scheme=</span><span class="attributevalue">"isoschematron"</span>&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;constraint&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"@artic"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"not(contains(., 'marc-stacc')) and not(contains(., 'ten-stacc'))"</span>&gt;</span>"
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;sch:value-of <span class="attribute">select=</span><span class="attributevalue">"."</span>/&gt;</span></div>" contains a deprecated value.<span data-indentation="5" class="element">&lt;/sch:assert&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/sch:rule&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"@artic.ges"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"not(contains(., 'marc-stacc')) and not(contains(., 'ten-stacc'))"</span>&gt;</span>"
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;sch:value-of <span class="attribute">select=</span><span class="attributevalue">"."</span>/&gt;</span></div>" contains a deprecated value.<span data-indentation="5" class="element">&lt;/sch:assert&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/sch:rule&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/constraint&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/constraintSpec&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/macroSpec&gt;</span></div></code></div>
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