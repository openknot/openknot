# Glossary of Terms
The goal for this document is to identify terms that may have multiple definitions due to how various implementations, silos or other uses "use" the term. Where it can it will identify the term in a concise as possible manner and also provide alternative definitions and see-also's to those uses.

### Person
A person is the human side of a [digital identifier](#Identity-(Digital)) and for the sake of Knot is just that - a person.

#### See Also
- [Identity (Digital)](#Identity-(Digital))

### Agent
[FOAF](http://xmlns.com/foaf/spec) defines an Agent as:

    Agent - An agent (eg. person, group, software or physical artifact). 

The W3C world also uses the term Principal for an Agent.

#### See Also
- http://xmlns.com/foaf/spec/#term_Agent
- http://www.w3.org/2005/Incubator/webid/wiki/Identity_Interoperability

### Digital Identity
A handle or identifier used to represent a person within a silo or federated space.

For example, the following are all digital identifiers:
- [Email Address](#Email-Address)
- [XMPP JID](#XMPP-JID) or Jabber ID
- AIM, ICQ
- Google+
- your personal domain used for [IndieAuth](http://indieauth.com/) or Persona
- GitHub username
- Facebook username

Digital identifiers can have associated with them the following attributes:
- Name: Full, First, Last, etc
- Phone number: Voice, SIP, Text
- Email: work, personal, etc.
- Physical address: work, personal
- Employer (can also be a digital identifier)

#### See Also
- https://xmpp.org/rfcs/rfc3921.html#VCARD
- http://indiewebcamp.com/OpenID
- http://indiewebcamp.com/ActivityStreams
- https://en.wikipedia.org/wiki/Digital_identity
- http://xmlns.com/foaf/spec/#term_Person

### Email Address
An email address is an identifier used to allow delivery via the [Internet Message Format](https://tools.ietf.org/html/rfc5322) an electronic mail message.

Email addresses are in the form of ```[ node "@" ] domain``` where ```node``` is a unique identifier within the  SMTP user address space for ```domain```.

Note: an email address may not lead directly to a person's "mailbox" but could lead to a mailing list or other silo that uses the email address format for delivery.

#### See Also
- https://tools.ietf.org/html/rfc5322
- https://en.wikipedia.org/wiki/Email_address

### XMPP JID
The [XMPP Core RFC](https://tools.ietf.org/html/rfc3920) defines a JID as:

    An entity is anything that can be considered a network endpoint
   (i.e., an ID on the network) and that can communicate using XMPP.
   All such entities are uniquely addressable in a form that is
   consistent with RFC 2396 [URI].  For historical reasons, the address
   of an XMPP entity is called a Jabber Identifier or JID.  A valid JID
   contains a set of ordered elements formed of a domain identifier,
   node identifier, and resource identifier.

A JID takes the form of ```[ node "@" ] domain [ "/" resource ]```.

#### See Also
- https://tools.ietf.org/html/rfc3920#section-3
