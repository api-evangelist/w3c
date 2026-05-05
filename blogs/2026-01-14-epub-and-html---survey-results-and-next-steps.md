---
title: "EPUB and HTML - Survey results and next steps"
url: "https://www.w3.org/blog/2026/epub-and-html-survey-results-and-next-steps/"
date: "Wed, 14 Jan 2026 12:38:00 +0000"
author: "Wendy Reid, co-Chair of the Publishing Maintenance Working Group, Susan Neuhaus, co-Chair of the Publishing Maintenance Working Group"
feed_url: "https://www.w3.org/blog/feed/"
---
<figure class="component component--image">
        <img alt="" src="https://www.w3.org/cms-uploads/_580xAUTO_crop_center-center_none/spencer-DXobXpIa9_4-unsplash.jpg" />
            <figcaption>
            <p>Photo by <a href="https://unsplash.com/@spen">Spencer</a></p>
        </figcaption>
    </figure>
                <div class="component component--text">
                    <p>
    Over the Northern Hemisphere summer of 2025, the Publishing Maintenance Working Group (PMWG) ran a survey in the publishing community to ask a question about a topic that has been lurking in our backlog for several years: should we allow HTML in EPUB?
</p>
<p>
    After reviewing and <a href="https://www.w3.org/2025/11/11-pmwg-minutes.html#e9a2">discussing those results</a> we have decided that we will not add HTML to EPUB 3.4.
</p>
<p>
    The survey results were invaluable in helping us come to this decision, and we deeply appreciate everyone who took the time to share and respond to our survey. We received compelling feedback both for and against the change. We know that our decision is going to make some people very happy and some people very unhappy, and we wanted to share how the feedback influenced our thinking, and what we want to do next.
</p>
<p>
    Before diving into the survey results, one thing we want to make clear is that the door is not closing on HTML and digital publications. In fact, the responses provided us important information that helped us realize that we need to take a new approach, one that I hope the community will consider supporting us in.
</p>
<p>
    We received over 100 responses from publishers, tool developers, reading system developers, independent authors, ebook retailers, social DRM providers, conversion vendors, distributors, and readers. The diversity of responses was instrumental in understanding how this change would impact various parts of the ecosystem.
</p>
<p>
    &nbsp;
</p>
<p>
    The primary arguments for the change included:
</p>
<ul>
    <li>
        Improved alignment with the web platform
    </li>
    <li>
        Opportunities for new tool and reading system developments
    </li>
    <li>
        Access to new toolsets or frameworks
    </li>
    <li>
        Ease barriers of understanding for a new generation of ebook developers
    </li>
    <li>
        Future-proofing EPUB, ensuring long-term support for files
    </li>
</ul>
<p>
    The arguments against the change included:
</p>
<ul>
    <li>
        Increased complexity for tooling, reading system, and distribution platforms
    </li>
    <li>
        Change may potentially break workflows for publishers, distribution, ingestion, or watermarking
    </li>
    <li>
        Industry investment has been focused on XML/XSLT technologies, adopting HTML would be expensive or prohibitive for some
    </li>
    <li>
        Interoperability concerns, older books no longer working on newly-developed reading systems or newer books not working on older systems
    </li>
</ul>
<p>
    In addition to the arguments for and against this change, we learned a great deal about the needs of the community, and it is these learnings that we want to take away to consider for the future.
</p>
<p>
    One of the most common requests in the feedback was for accompanying best practices, sample files, test suites, and supplemental information on what HTML might look like in EPUB. In addition to these asks, we heard that people wanted to know more about the features that would be implemented and supported by reading systems, or whether we might consider defining a subset of HTML and CSS instead of adopting HTML wholesale.
</p>
<p>
    We also learned that there remains a great deal of misinformation out there about EPUB's current relationship with HTML. For over a decade, EPUB3 has supported what is specifically known as the XML serialization of HTML, not XHTML 1.1. What this means is that EPUB already supports most of the current HTML specification, including elements like `&lt;video&gt;`. For more information, we invite you to read about EPUB's <a href="https://www.w3.org/TR/epub-34/#sec-overview-relations-html">relationship to HTML</a>.
</p>
<p>
    The publishing ecosystem is different from the web. There are more technologies and stakeholders between an ebook and its reader than there are between a website and its visitor. For instance, there are specialized tools that serve authors and publishers who don't write code. Additionally, ebooks must be compatible with a myriad of libraries and booksellers. Therefore, making this change has a greater potential to break tools and workflows than a similar change in the web environment.
</p>
<p>
    EPUB must maintain backwards compatibility. This makes sense in the book world, where content is less dynamic than a website. A book's content is more likely to stay the same, or very similar, throughout the lifetime of the book. Consistency is an expected feature of books. This consistency is important for archiving and preservation. Backwards compatibility makes adopting HTML in EPUB more difficult, too.
</p>
<p>
    What happens next? We do not want to close the door on this discussion entirely, especially because the gaps identified by a number of respondents are important to acknowledge. There are feature gaps in EPUB that HTML integration could have addressed, but in discussing these gaps, we realized that simply adding HTML would not address the underlying problems. Much of the excitement expressed for this change came from people looking to do more than EPUB currently allows or has broad support for, like scripting or interactivity, or from use cases like web publications.
</p>
<p>
    We encourage anyone interested in the future of digital publications and EPUB to join the <a href="https://www.w3.org/community/publishingcg/">Publishing Community Group</a> and share their use cases and issues with us. It's important for us to understand what people want to do, or what they are already doing but having challenges with, so we can look for solutions that become specifications. We look forward to learning and working with people interested in what digital publications can be!
</p>
            </div>
