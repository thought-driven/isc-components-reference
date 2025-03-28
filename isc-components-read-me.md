# ISLG Custom Squarespace Components

## Setup

ISLG's Custom Components utilize code injection to function.
When code blocks with specific attributes are added to a page, the injected code processes and renders them correctly.

To enable custom components on a new page, follow these steps:

1. Copy the injected code from any page that uses custom components already (found in Page Settings -> Advanced -> Page Header Code Injection).

2. Paste the code into the Page Code Injection field of the new page.

## Table of Contents

1. [Acknowledgements](#acknowledgements)
2. [Authors](#authors)
3. [BottomNav](#bottomnav)
4. [Button](#button)
5. [CenterText](#centertext)
6. [CenteredEmbed](#centeredembed)
7. [Heading](#heading)
8. [Footnote](#footnote)
9. [Header](#header)
10. [Paragraph](#paragraph)
11. [Sticky2Column](#sticky2column)
12. [Sticky2ColumnEmbed](#sticky2columnembed)
13. [Sticky2ColumnSidebar](#sticky2columnsidebar)
14. [TableOfContents](#tableofcontents)
15. [TextWithImage](#textwithimage)
16. [Tooltip](#tooltip)

## Acknowledgements

![Image](https://github.com/user-attachments/assets/1d2a2f66-e367-4e94-aafa-99558e889d36)

```html
<div class="isc-acknowledgements">
  <div class="data">
    <div data-title>Acknowledgements</div>
    <div data-image data-image-url="https://your-image-url"></div>
    <div data-content>
      <p>First paragraph</p>
      <p>Second paragraph</p>
      <p>Third paragraph</p>
    </div>
  </div>
</div>
```

## Authors

![Image](https://github.com/user-attachments/assets/3dfc3cfa-9bd1-440f-9d0c-724766de0e05)

```html
<div class="isc-authors">
  <div class="data">
    <div data-description>Listed in alphabetical order</div>
    <div data-content>
      <div
        data-author
        data-name="Alison Diéguez"
        data-role="CUNY Institute for State and Local Governance"
        data-avatar-url="https://avatar-image-1"
      ></div>
      <div
        data-author
        data-name="Brian Holliday"
        data-role="CUNY Institute for State and Local Governance"
        data-avatar-url="https://avatar-image-2"
      ></div>
      <div
        data-author
        data-name="Kate Jassin"
        data-role="CUNY Institute for State and Local Governance"
        data-avatar-url="https://avatar-image-3"
      ></div>
    </div>
  </div>
</div>
```

## BottomNav

![Image](https://github.com/user-attachments/assets/c3295427-c3bb-4c43-9477-411d348c1e63)

```html
<div class="isc-bottom-nav">
  <div class="data">
    <div data-nav-button data-url="https://www.google.com">
      Back to Resources
    </div>
  </div>
</div>
```

## Button

![Image](https://github.com/user-attachments/assets/a5e6d035-ca51-4032-8cfc-b0c7b9abc6fe)

```html
<div class="isc-button">
  <div class="data">
    <div
      data-button
      data-button-text="DOWNLOAD A PDF OF THE REPORT"
      data-button-url="https://www.google.com/"
    ></div>
  </div>
</div>
```

## CenterText

![Image](https://github.com/user-attachments/assets/af01cd10-52f9-42fc-91fc-de11cad574ae)

```html
<div class="isc-center-text">
  <div class="data">
    <div data-margins data-margin-top="0px" data-margin-bottom="70px"></div>
    <div data-background data-background-color="#ffffff"></div>
    <div data-content>
      <p>First Paragraph</p>
      <span>This will be set as a pull quote</span>
      <p>Second Paragraph</p>
    </div>
  </div>
</div>
```

## CenteredEmbed

![Image](https://github.com/user-attachments/assets/9cabd0a3-24e4-457f-9929-a45706d0e0bf)

```html
<div class="isc-centered-embed">
  <div class="data">
    <div data-flip data-flip-columns="false"></div>
    <div
      data-embed
      data-iframe-url="https://datawrapper.dwcdn.net/graphcode"
    ></div>
    <div data-content>
      <p>First Paragraph</p>
      <p>Second Paragraph</p>
    </div>
  </div>
</div>
```

## Heading

![Image](https://github.com/user-attachments/assets/91734352-e0c3-4426-ba34-9da1f0c33af2)

```html
<div class="isc-chapter-heading">
  <div class="data">
    <div data-margins data-margin-top="80px" data-margin-bottom="80px"></div>
    <div data-title>Occupation Trends Across the Workforce</div>
  </div>
</div>
```

## Footnote

![Image](https://github.com/user-attachments/assets/e271ca19-d7d1-49f4-a971-4b58bf0d97f8)

The footnote component can be embedded inside other components like isc-header.
Like the table of contents component, or the tooltip component, it does not need its own code block.

```html
<div class="isc-footnote">
  <div class="data">
    <div data-footnote data-footnote-id="i">First footnote content</div>
    <div data-footnote data-footnote-id="ii">Second footnote content</div>
    <div data-footnote data-footnote-id="iii">Third footnote content</div>
  </div>
</div>
```

```html
<p>
  Setting a footnote within any paragraph element. The roman numeral inside the
  sup element will be matched for content.<sup isc-footnote-sup>i</sup>
</p>
```

## Header

![Image](https://github.com/user-attachments/assets/45d1251a-7ef9-4286-b057-c743da0f6e67)

```html
<div class="isc-header">
  <div class="data">
    <div data-top>RESEARCH BRIEF</div>
    <div data-date data-month="2" data-year="2025"></div>
    <div data-title>Critical Services, High Growth, Low Wages</div>
    <div data-subtitle>
      Employment and Wage Trends Across New York’s Human Services Workforce
    </div>
  </div>
</div>
```

## Paragraph

![Image](https://github.com/user-attachments/assets/fb17a605-8235-4a6c-a589-6d4b0a412e40)

```html
<div class="isc-paragraph">
  <div class="data">
    <div data-margins data-margin-top="80px" data-margin-bottom="80px"></div>
    <div data-content>
      <p>
        New York’s human services sector is crucial to the state’s social
        fabric...
      </p>
    </div>
  </div>
</div>
```

## Sticky2Column

![Image](https://github.com/user-attachments/assets/8ef756e3-54d4-4f06-9b7c-7a41883a6185)

```html
<div class="isc-sticky-2-column">
  <div class="data">
    <div data-flip data-flip-columns="false"></div>
    <div data-width data-text-width-percent="50"></div>
    <div data-mobile data-viz-position="2"></div>
    <div data-viz data-viz-url="https://image-url"></div>
    <div data-viz-overlay-text>
      Despite the importance of these services, wages in the human services...
    </div>
    <div data-content>
      <p>
        New York’s human services sector is crucial to the state’s social
        fabric...
      </p>
      <p>
        Second paragraph has a link to an external source
        <a
          target="_blank"
          rel="noopener noreferrer"
          href="https://external-link"
          >and opens on a new tab</a
        >
      </p>
      <p>Third paragraph...</p>
    </div>
  </div>
</div>
```

## 25/75 Embed

![Image](https://github.com/user-attachments/assets/e96d94e5-802e-4ef2-a214-45975a1772bd)

```html
<div class="isc-sticky-2-column-embed">
  <div class="data">
    <div data-flip data-flip-columns="true"></div>
    <div
      data-embed
      data-iframe-url="https://datawrapper.dwcdn.net/ graphcode"
    ></div>
    <div data-content>
      <p>
        Home Health Aides make up most of New York State's human services
        workforce (Figure 7). Health Aide, Nursing Assistant, or Childcare
        Worker.<sup isc-footnote-sup>vi</sup>
      </p>
    </div>
  </div>
</div>
```

## Sticky2ColumnSidebar

![Image](https://github.com/user-attachments/assets/677c17a1-4b08-418d-8459-8a42cbbfef00)

```html
<div class="isc-sticky-2-column-sidebar">
  <div class="data">
    <div data-margins data-margin-top="70px" data-margin-bottom="70px"></div>
    <div data-viz data-viz-url="https://image-url"></div>
    <div data-sidebar-title>What are human services?</div>
    <div data-mobile data-sidebar-position="1"></div>
    <div data-sidebar-content>
      <p>This will be the contents inside the sidebar.</p>
    </div>
    <div data-content>
      <p>First paragraph...</p>
      <h3>H3s can be added</h3>
      <ol>
        <li>
          <b>As well as b elements for bold</b>
          And list items for ordered (ol elements) and unordered lists (ul
          elements)
        </li>
      </ol>
      <ul>
        <li></li>
      </ul>
    </div>
  </div>
</div>
```

## TableOfContents

![Image](https://github.com/user-attachments/assets/06c5a951-6eb2-4924-81f1-64bb922a1b47)
![Image](https://github.com/user-attachments/assets/e0d4d71a-1b9c-44a8-8ba2-951472e8ec84)
![Image](https://github.com/user-attachments/assets/aec048a1-f9ac-4ae4-8022-7bf8d1643ea9)

The TableOfContents component automatically generates a navigable list of headings from your page content.
Unlike other components, it:

1. Does not require a nested .data div or additional data attributes
2. Can be embedded inside other components like isc-header or at the top level of your document. It does not need its own code block.
3. Will automatically scan the page for headings and create anchor links to them.

```html
<div class="isc-table-of-contents"></div>
```

## TextWithImage

![Image](https://github.com/user-attachments/assets/16c8bfa3-779b-4d54-a539-be08aa98dd1c)

```html
<div class="isc-text-with-image">
  <div class="data">
    <div
      data-title
      data-title-text="Defining the human services workforce"
    ></div>
    <div data-image data-image-url="https://image-url"></div>
    <div data-content>
      <p>First paragraph</p>
      <span>
        Whatever is inside a span element will be treated as a pull quote and
        will be placed in the order it appears within the data content.
      </span>
      <p>Second paragraph</p>
    </div>
  </div>
</div>
```

## Tooltip

![Image](https://github.com/user-attachments/assets/deb6ffb9-b1f1-493d-8c95-6f828e5d0bc5)
The tooltip component can be embedded inside other components like isc-header.
Like the table of contents component, or the footnote component, it does not need its own code block.

```html
<div class="isc-tooltip">
  <div class="data">
    <div data-tooltip data-tooltip-id="1">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus cursus
      placerat consectetur.
    </div>
    <div data-tooltip data-tooltip-id="2">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus cursus
      placerat consectetur. Donec maximus mi id diam laoreet auctor.
    </div>
  </div>
</div>
```

```html
<sup isc-tooltip-sup data-tooltip-id="1">^</sup>
```
