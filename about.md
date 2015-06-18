---
layout: flat
title: About TAXII
toc: about_toc.html
---

Trusted Automated eXchange of Indicator Information (TAXII™) is a set of services and message exchanges that ensures secure transport of cyber threat information for both new and existing information sharing communities. In TAXII, individual services are optional for any given implementation, allowing enterprises to include only the services desired for their particular sharing model.

TAXII supports both push and pull messaging in all sharing models, including:

<div class="row">
  <div class="col-lg-4 col-md-6">
    <div class="panel panel-default">
      </div>
      <div class="panel-body">
        <p><strong>Hub and Spoke</strong> is a sharing model where one organization functions as the central clearinghouse for information, or hub, coordinating information exchange between partner organizations, or spokes. Spokes can produce and/or consume information from the Hub.</p>
        <div class="text-center">
          <img src="/images/hub_and_spoke.png" width="300" alt="Hub and Spoke Model" />
        </div>
      </div>
    </div>
  </div>
    </div>
  <div class="col-lg-4 col-md-6">
    <div class="panel panel-default">
      </div>
      <div class="panel-body">
        <p><strong>Source/Subscriber</strong> is a sharing model where one organization functions as the single source of information and sends that information to subscribers.</p>
        <div class="text-center">
          <img src="/images/source_subscriber.png" width="300" alt="Source/Subscriber Model" />
        </div>
      </div>
    </div>
  </div>
   <div class="col-lg-4 col-md-6">
    <div class="panel panel-default">
      </div>
      <div class="panel-body">
        <p><strong>Peer to Peer</strong> is a sharing model where two or more organizations share information directly with one another. A Peer to Peer sharing model may be ad-hoc, where information exchange is not coordinated ahead of time and is done on an as-needed basis, may be well defined with legal agreements and established procedures, or somewhere in the middle.</p>
        <div class="text-center">
          <img src="/images/peer_to_peer.png" width="300" alt="Peer to Peer Model" />
        </div>
      </div>
    </div>
  </div>
</div> 
  
The [TAXII White Paper](http://taxiiproject.github.io/getting-started/whitepaper) explains why TAXII was developed, the problems TAXII solves, how TAXII solves those problems, and the sharing groups that will benefit from using TAXII. The whitepaper also goes into detail on the individual components of TAXII and how they fit together.

### TAXII Community

TAXII is a collaborative effort driven by an open community. Community members make open-source contributions to TAXII development and manage issue tracking for the TAXII Specifications, tools, and supporting information. 

[Join the community](http://taxiiproject.github.io/community/) today.

## Frequently Asked Questions

#### What can I do with TAXII?
TAXII implementations enable secure, consistent, and automated exchange of cyber threat information. TAXII services can be used to support a wide range of sharing models and community requirements. With standardized services, messages, and message exchanges, TAXII implementations facilitate automation and eliminate the need for multiple, custom, point-to-point exchange implementations. TAXII simplifies and speeds cyber threat information exchange.

In addition, TAXII is the preferred method of exchanging information represented using the [Structured Threat Information Expression (STIX™)](http://stixproject.github.io/) language, enabling organizations to share structured cyber threat information in a secure and automated manner.

#### How do I get TAXII?

The TAXII Specifications, documentation, and related information is currently available on the [TAXII website](https://taxii.mitre.org/). Additional materials are also hosted in [TAXIIProject on GitHub.com](https://github.com/TAXIIProject).

#### Where can I find sample uses of TAXII? Are there any TAXII repositories?

The [TAXII Samples]( http://taxiiproject.github.io/documentation/sample-use/) page on this website contains sample HTTP Request/Responses for TAXII. Please note that these examples do not demonstrate the full spectrum of TAXII capabilities. Each type of TAXII Message is listed at least once.

In addition to the MITRE samples, community members have set up TAXII repositories containing TAXII and STIX content and even directories pointing to those repositories. One example repository is [http://hailataxii.com](http://hailataxii.com).

#### How do I use TAXII? What tools/utilities are available for this effort?

The primary way to use TAXII is via commercial products. See the [STIX/TAXII Supporters page](http://stixproject.github.io/supporters) on the [STIX website](http://stixproject.github.io/) for a list.

Tools and utilities are available in the [TAXII GitHub Repositories](https://github.com/TAXIIProject/).

#### Which products/services and communities are using TAXII?

The [many organizations](http://stixproject.github.io/supporters) that are using or have announced support for TAXII and STIX are listed on our combined [STIX/TAXII Supporters page](http://stixproject.github.io/supporters), which is hosted on the [STIX website](http://stixproject.github.io/). Please fill out this form to contact the TAXII Team and request inclusion or modification under [User Communities](User Communities) or [Products and Services](http://stixproject.github.io/supporters/#products-and-serv).

The [STIX-TAXII-CybOX-MAEC News/Blog](http://stixproject.tumblr.com/) also lists press releases and other vendor announcements.

#### Who funds TAXII?

TAXII is currently led by the [Office of Cybersecurity and Communications](http://www.dhs.gov/office-cybersecurity-and-communications/) at the [U.S. Department of Homeland Security](http://www.dhs.gov/). DHS sponsors the [Homeland Security Systems Engineering and Development Institute (HSSEDI)]( http://www.mitre.org/centers/homeland-security-systems-engineering-and-development-institute), operated by The MITRE Corporation, to manage the TAXII project.

#### Who owns TAXII?

TAXII is an open-source, community effort currently led and sponsored by the office of Cybersecurity and Communications at the U.S. Department of Homeland Security. MITRE has copyrighted the TAXII Specifications (currently hosted on the [https://taxii.mitre.org/](https://taxii.mitre.org/) website) for the benefit of the community in order to ensure it remains a free and open standard, as well as to legally protect the ongoing use of it and any resulting content by government, vendors, and/or users. In addition, MITRE has trademarked ™ the TAXII acronym and the TAXII logo to protect their sole and ongoing use by the TAXII effort within the information security arena.

#### How is TAXII licensed?

See the [Terms of Use](https://taxii.mitre.org/about/termsofuse.html).

## Relationship to Other Efforts

#### STIX

[Structured Threat Information eXpression (STIX™)](http://stixproject.github.io/) is a structured language to characterize the full range of cyber threat information. STIX is one payload that TAXII can convey. STIX represents cyber threat information in a standardized and structured manner. STIX characterizes what is being shared, while TAXII defines how the STIX payload is shared.

The STIX and TAXII communities work closely together (and in fact consist of many of the same people) to ensure that they continue to provide a full stack for sharing threat intelligence.

#### CybOX

[Cyber Oberservable eXpression (CybOX™)](http://cyboxproject.github.io/) provides a structured language for describing elements within the cyber operational environment. [STIX](http://stixproject.github.io/) is one payload that TAXII can convey, and STIX uses CybOX to represent cyber observables.

#### MAEC
[Malware Attribute Enumeration and Characterization (MAEC™)](http://maecproject.github.io/) is a [U.S. Department of Homeland Security](http://www.dhs.gov/)—led effort of the office of [Cybersecurity and Communications](http://www.dhs.gov/office-cybersecurity-and-communications/) that provides a standardized language for encoding and communicating high-fidelity information about malware based upon attributes such as behaviors, artifacts, and attack patterns. [STIX](http://stixproject.github.io/) is one payload that TAXII can convey, and STIX can describe malware using MAEC.
