---
layout: sidebar
sidebar: s1
version: "v3"
title: "fermata"

---

<div class="elementSpec">
   <h3 id="fermata">&lt;fermata&gt;</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">&lt;fermata&gt;</span> An indication placed over a note or rest to indicate that it should be held longer
            than
            its written value. May also occur over a bar line to indicate the end of a phrase
            or
            section. Sometimes called a 'hold' or 'pause'.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI.cmn</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Attributes</span>
         </td>
         <td class="wovenodd-col2">
            <div class="attributeDef">
               <span class="attribute">@altsym</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a way of pointing to a user-defined symbol. It must contain an ID of a
                  &lt;symbolDef&gt; element elsewhere in the document.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.altsym">att.altsym</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@color</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to indicate visual appearance. Do not confuse this with the musical term
                  'color' as used in pre-CMN notation.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.COLOR">data.COLOR</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.color">att.color</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@copyof</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to an element of which the current element is a copy.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@corresp</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to point to other elements that correspond to this one in a generic
                  fashion.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@dur.ges</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records performed duration information that differs from the written duration. Its
                  value may be expressed in several forms; that is, ppq (MIDI clicks and MusicXML
                  'divisions'), Humdrum **recip values, beats, seconds, or mensural duration
                  values.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.DURATION.gestural">data.DURATION.gestural</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.duration.performed">att.duration.performed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@endid</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the final element in a sequence of events to which the feature
                  applies.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.startendid">att.startendid</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@evaluate</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Specifies the intended meaning when a participant in a relationship is itself a
                  pointer.
               </span>
               Allowed values are:
               "
               <span style="font-weight: 500;">all</span>" 
               <i>(If an element pointed to is itself a pointer, then the target of that pointer
                  will be taken, and so on, until an element is found which is not a pointer.)
               </i>,  "
               <span style="font-weight: 500;">one</span>" 
               <i>(If an element pointed to is itself a pointer, then its target (whether a pointer
                  or not) is taken as the target of this pointer.)
               </i>,  "
               <span style="font-weight: 500;">none</span>" 
               <i>(No further evaluation of targets is carried out beyond that needed to find the
                  element(s) specified in plist or target attribute.)
               </i>
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.targeteval">att.targeteval</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@facs</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Permits the current element to reference a facsimile surface or image zone which
                  corresponds to it.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.facsimile">att.facsimile</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontfam</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Contains the name of a font-family.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.FONTFAMILY">data.FONTFAMILY</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontname</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Holds the name of a font.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.FONTNAME">data.FONTNAME</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontsize</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch,
                  relative terms, e.g., "small", "larger", etc., or percentage values relative to "normal"
                  size, e.g., "125%". 
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.FONTSIZE">data.FONTSIZE</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontstyle</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records the style of a font, i.e, italic, oblique, or normal.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.FONTSTYLE">data.FONTSTYLE</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@fontweight</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to indicate bold type.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.FONTWEIGHT">data.FONTWEIGHT</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.typography">att.typography</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@form</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the visual appearance of the fermata; that is, whether it occurs as
                  upright or inverted.
               </span>
               Allowed values are:
               "
               <span style="font-weight: 500;">inv</span>" 
               <i>(Inverted, i.e., curve or bracket below the dot.)</i>,  "
               <span style="font-weight: 500;">norm</span>" 
               <i>(Upright; i.e., curve or bracket above the dot.)</i>
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.fermata.vis">att.fermata.vis</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@glyphname</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Glyph name.</span>
               Value of datatype 
               <span style="font-weight: 500;">string</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.extsym">att.extsym</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@glyphnum</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Numeric glyph reference in hexadecimal notation, e.g. "#xE000" or "U+E000". N.B.
                  SMuFL version 1.18 uses the range U+E000 - U+ECBF.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">
                  a string matching the following regular expression: "(#x|U\+)[A-F0-9]+"
                  
               </span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.extsym">att.extsym</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@ho</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a horizontal adjustment to a feature's programmatically-determined location
                  in terms of staff interline distance; that is, in units of 1/2 the distance between
                  adjacent staff lines.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.visualoffset.ho">att.visualoffset.ho</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@label</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a name or label for an element. The value may be any string.</span>
               Value of datatype 
               <span style="font-weight: 500;">string</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@layer</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Identifies the layer to which a feature applies.</span>
               One or more values of datatype 
               <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.layerident">att.layerident</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@n</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a number-like designation for an element.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/token">token</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.common">att.common</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@next</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to point to the next event(s) in a user-defined collection.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@place</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Captures the placement of the item with respect to the staff with which it is
                  associated.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.STAFFREL">data.STAFFREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.placement">att.placement</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@plist</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Contains a space separated list of references that identify active participants in
                  a
                  collection/relationship, such as notes under a phrase mark; that is, the entities
                  pointed "from".
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.plist">att.plist</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@prev</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to the previous event(s) in a user-defined collection.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@sameas</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to an element that is the same as the current element but is not a literal
                  copy of the current element.
               </span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@shape</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Describes the visual appearance of the fermata; that is, whether it has a curved,
                  square, or angular shape.
               </span>
               Allowed values are:
               "
               <span style="font-weight: 500;">curved</span>" 
               <i>(A curve above or below the dot.)</i>,  "
               <span style="font-weight: 500;">square</span>" 
               <i>(A bracket above or below the dot.)</i>,  "
               <span style="font-weight: 500;">angular</span>" 
               <i>(A triangle above or below the dot.)</i>
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.fermata.vis">att.fermata.vis</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@staff</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Signifies the staff on which a notated event occurs or to which a control event
                  applies. Mandatory when applicable.
               </span>
               One or more values of datatype 
               <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.staffident">att.staffident</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@startid</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Holds a reference to the first element in a sequence of events to which the feature
                  applies.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.startid">att.startid</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@subtype</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provide any sub-classification for the element, additional to that given by its type
                  attribute.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">NMTOKEN</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.typed">att.typed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@synch</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Points to elements that are synchronous with the current element.</span>
               One or more values from
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>, separated by spaces.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.common.anl">att.common.anl</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@to</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a timestamp adjustment of a feature's programmatically-determined location
                  in terms of musical time; that is, beats.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.TSTAMPOFFSET">data.TSTAMPOFFSET</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.visualoffset.to">att.visualoffset.to</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@tstamp</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes the onset time in terms of musical time, i.e.,
                  beats[.fractional_beat_part].
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.BEAT">data.BEAT</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.timestamp.musical">att.timestamp.musical</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@tstamp.ges</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Captures performed onset time in several forms; that is, ppq (MIDI clicks and
                  MusicXML 'divisions'), Humdrum **recip values, beats, seconds, or mensural duration
                  values.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.DURATION.gestural">data.DURATION.gestural</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.timestamp.performed">att.timestamp.performed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@tstamp.real</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Used to record the onset time in terms of ISO time.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.ISOTIME">data.ISOTIME</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.timestamp.performed">att.timestamp.performed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@type</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Characterizes the element in some sense, using any convenient classification scheme
                  or typology.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">NMTOKEN</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.typed">att.typed</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@vo</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records the vertical adjustment of a feature's programmatically-determined location
                  in terms of staff interline distance; that is, in units of 1/2 the distance between
                  adjacent staff lines.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.visualoffset.vo">att.visualoffset.vo</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@when</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Indicates the point of occurrence of this feature along a time line. Its value must
                  be the ID of a 
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/when">when</a> element elsewhere in the document.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.alignment">att.alignment</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@x</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes an x coordinate for a feature in an output coordinate system. When it is
                  necessary to record the placement of a feature in a facsimile image, use the facs
                  attribute.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">decimal</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.xy">att.xy</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:base</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Provides a base URI reference with which applications can resolve relative URI
                  references into absolute URI references.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.URI">data.URI</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.commonPart">att.commonPart</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@xml:id</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Regularizes the naming of an element and thus facilitates building links between it
                  and other resources. Each id attribute within a document must have a unique
                  value.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">ID</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.id">att.id</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@y</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Encodes an y coordinate for a feature in an output coordinate system. When it is
                  necessary to record the placement of a feature in a facsimile image, use the facs
                  attribute.
               </span>
               Value of datatype 
               <span style="font-weight: 500;">decimal</span>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.xy">att.xy</a>
               </span>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Member of</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="/{{ page.version }}/model.controleventLike.cmn">model.controleventLike.cmn</a>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Contained by</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div class="specChildren">
                  <div class="specChild">
                     <span class="specChildModule">MEI.cmn</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/arpeg">arpeg</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/beamSpan">beamSpan</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/bend">bend</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/breath">breath</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/fermata">fermata</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/gliss">gliss</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/hairpin">hairpin</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/harpPedal">harpPedal</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/measure">measure</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/octave">octave</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/pedal">pedal</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/reh">reh</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/slur">slur</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/tie">tie</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/tupletSpan">tupletSpan</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.critapp</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/lem">lem</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/rdg">rdg</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.edittrans</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/abbr">abbr</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/add">add</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/corr">corr</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/cpMark">cpMark</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/damage">damage</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/del">del</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/expan">expan</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/orig">orig</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/reg">reg</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/restore">restore</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/sic">sic</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/supplied">supplied</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/unclear">unclear</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.mensural</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/ligature">ligature</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.neumes</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/syllable">syllable</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.shared</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/dir">dir</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/dynam">dynam</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/layer">layer</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/ornam">ornam</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/phrase">phrase</a> 
                        <a class="link_odd_elementSpec" href="/{{ page.version }}/tempo">tempo</a>
                     </span>
                  </div>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">May contain</span>
         </td>
         <td class="wovenodd-col2">
            <div class="specChild">
               <span class="specChildModule">Empty</span>
               <span class="specChildElements"></span>
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
                  <span data-indentation="1" class="element">&lt;classes&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.common">att.common</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.facsimile">att.facsimile</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.fermata.log">att.fermata.log</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.fermata.vis">att.fermata.vis</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.fermata.ges">att.fermata.ges</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.fermata.anl">att.fermata.anl</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.typed">att.typed</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/model.controleventLike.cmn">model.controleventLike.cmn</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/classes&gt;</span>
               </div>
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:empty/&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Remarks</span>
         </td>
         <td class="wovenodd-col2">
            <p>The 
               <a class="link_odd_elementSpec" href="/{{ page.version }}/fermata">fermata</a> element is a specialized form of, i.e., syntactic sugar
               for, dir/@type="fermata" with &amp;ferm; or &amp;uferm; as its PCDATA content. The
               
               <span class="att">shape</span> attribute may be used to record whether the fermata is curved or
               square. Other visual forms of a fermata may be indicated via the 
               <span class="att">altsym</span>
               attribute. The starting point of the fermata may be indicated by either a
               
               <span class="att">startid</span>, 
               <span class="att">tstamp</span>, 
               <span class="att">tstamp.ges</span>, or 
               <span class="att">tstamp.real</span>
               attribute. It is a semantic error not to specify a starting point attribute.
            </p>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Constraints</span>
         </td>
         <td class="wovenodd-col2">
            <div>
               <div>Must have one of the attributes: startid, tstamp, tstamp.ges or tstamp.real.</div>
            </div>
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;sch:rule 
                     <span class="attribute">context=</span>
                     <span class="attributevalue">"mei:fermata"</span>&gt;
                  </span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;sch:assert 
                        <span class="attribute">test=</span>
                        <span class="attributevalue">"@startid or @tstamp or @tstamp.ges or @tstamp.real"</span>&gt;
                     </span>Must have one of
                     the attributes: startid, tstamp, tstamp.ges or tstamp.real.
                     <span data-indentation="2" class="element">&lt;/sch:assert&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/sch:rule&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>