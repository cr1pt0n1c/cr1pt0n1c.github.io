# The Invisible Battlefield: Decrypting the BIS 2025 Annual Report

I didn't read the BIS 2025 Annual Report looking for politics. I wasn't interested in diplomatic statements, geopolitical theory, or trying to predict what governments are going to do next.

I read it as a cybersecurity person.

I wanted to know where the attacks actually happen. What gets targeted? What techniques are being used? And more importantly, what happens when cyberattacks, social engineering, espionage, disinformation, and physical operations stop being separate problems and start becoming parts of the same attack chain?

And that's what makes the report genuinely interesting.

Because the biggest lesson isn't that Russia conducts cyberattacks, China conducts espionage, or that disinformation exists. We already know that.

The disturbing part is **how well all of these things fit together.**

The modern battlefield doesn't necessarily look like a battlefield anymore.

Sometimes it looks like an email inbox.

Sometimes it looks like a LinkedIn message.

Sometimes it looks like a TikTok account.

Sometimes it looks like a water pump connected to the internet.

And sometimes, it looks like an ordinary person who has absolutely no idea that they have just become part of someone else's operation.

## The Attack Surface is Human

One of the things that immediately caught my attention was how BIS describes Russian cyber operations against Czech targets.

Technical vulnerabilities. Human errors. Social engineering. Authentication weaknesses.

All sitting next to each other.

From a Red Team perspective, this shouldn't be surprising. But it should be uncomfortable.

We spend enormous amounts of money building firewalls, deploying EDR, segmenting networks, patching servers, and monitoring endpoints.

And then someone sends an employee a convincing message.

Suddenly, the most sophisticated infrastructure in the world can be sitting behind a person who has been psychologically manipulated into opening the front door.

We like to describe users as the "weakest link."

I think that's the wrong way to look at it.

**The human isn't a flaw in the architecture. The human is part of the architecture.**

If your security model assumes that every employee will make the correct decision every single time, you don't have a security architecture.

You have a hope-based authentication system.

## APTs Don't Have to Be Loud

The report also highlights state-sponsored groups such as Russia's APT28, associated with the GRU, targeting Czech organizations including logistics and technology companies.

But China's APT31 activity demonstrates something even more interesting.

Long-term access.

Silence.

Espionage.

The average person has been conditioned to think of hacking as something dramatic. Servers go down. Files get encrypted. Screens turn red. Someone demands cryptocurrency.

That's ransomware.

That's not necessarily what a nation-state wants.

A successful Advanced Persistent Threat doesn't have to destroy anything.

It might simply sit there.

Watching.

Collecting.

Learning.

Extracting information over a long period of time without creating enough noise to trigger a response.

And that's a completely different threat model.

**The most valuable payload isn't always destruction. Sometimes it's information.**

A compromised server that crashes tomorrow might be less valuable than a compromised system that nobody notices for six months.

## Social Engineering as Statecraft

This is where the report gets particularly interesting from a social-engineering perspective.

BIS describes Chinese intelligence activity involving academia and professional platforms such as LinkedIn. Targets can be approached through apparently legitimate professional opportunities, cooperation, or networking before the conversation gradually moves toward requests for sensitive information.

Think about how different that is from the stereotypical phishing email.

There is no obvious Nigerian prince.

No ridiculous spelling mistakes.

No suspicious attachment called `definitely_not_malware.exe`.

The attacker doesn't necessarily need to create panic.

They can create **trust**.

And that changes the entire attack chain.

**OSINT → Targeting → Relationship Building → Trust → Information Extraction**

The attacker doesn't break through the door.

They convince you to open it.

That's social engineering at a completely different scale.

## OSINT Is More Than Finding Open Ports

Cybersecurity people sometimes reduce OSINT to finding exposed infrastructure.

Subdomains.

IP addresses.

Leaked credentials.

Open ports.

Metadata.

Interesting, useful, but incomplete.

The BIS report demonstrates another dimension of reconnaissance: **mapping people.**

Who works for the organization?

What is their position?

What information can they access?

What projects are they involved in?

Who do they know?

Which conferences do they attend?

What professional interests do they publicly discuss?

Who would they trust?

That's an entirely different attack surface.

For an ethical hacker performing reconnaissance, the organization isn't just a collection of servers.

It's a collection of humans connected by relationships.

And those relationships can be mapped just like a network.

## Information Laundering

Then we move from cyber operations into the information space.

BIS describes an interconnected ecosystem of disinformation websites that repeatedly reference and reinforce one another.

At first glance, this might look like multiple sources reporting the same story.

It isn't necessarily.

Imagine this:

*Source → Website A → Website B → Website C → Social Media → Influencer → Wider Media*

By the time the information reaches the average person, the original source may be almost impossible to see.

The claim now appears to have been "reported everywhere."

But repetition isn't verification.

Ten websites repeating the same fabricated claim don't create ten independent sources.

They create **one claim with ten amplification layers.**

This is what makes information laundering so dangerous.

The payload doesn't need to remain attached to its original source.

It just needs to survive long enough to become familiar.

## The Algorithm Is Now Part of the Attack Surface

This might be one of the most interesting parts of the report from a cybersecurity perspective.

BIS describes networks of fake TikTok accounts pushing anti-system and pro-Russian narratives while artificially interacting with each other to increase the visibility of their content.

Think about what that actually means.

The attacker doesn't necessarily need to compromise TikTok.

They don't need administrator access.

They don't need to exploit a kernel vulnerability.

They simply need to understand the system well enough to manipulate the environment around it.

That's a fascinating shift.

In traditional cybersecurity, we protect the infrastructure.

Servers.

Networks.

Applications.

APIs.

But recommendation systems are infrastructure too.

If an attacker can manipulate what millions of people are shown without compromising the underlying platform, they have achieved something arguably more interesting than a conventional breach.

**They haven't hacked the server. They've hacked the information flow.**

The algorithm itself becomes part of the attack surface.

## Hacktivism and the Hybrid Chain

Russian hacktivist groups have repeatedly used DDoS attacks against Czech organizations.

Technically?

Often not particularly impressive.

DDoS isn't exactly the pinnacle of offensive cybersecurity.

But that's missing the point.

Cyber operations don't necessarily need to be technically sophisticated to be strategically useful.

Imagine a government website becomes unavailable.

The attack gets reported.

News outlets pick it up.

People start discussing it.

The public sees headlines about another Russian cyberattack.

Suddenly, a relatively simple technical incident has become part of a much larger psychological operation.

The technical effect might last an hour.

The psychological effect can last much longer.

**The server is the target, but the audience is the payload.**

That's the part cybersecurity teams sometimes forget.

## The Anatomy of Hybrid Warfare

This is where everything starts connecting.

Cyberattack.

Propaganda.

Social engineering.

Espionage.

Physical sabotage.

Individually, these are different disciplines.

Together, they become a system.

BIS describes cases in which individuals were recruited through platforms such as Telegram to conduct physical acts of sabotage, with the operation being documented and subsequently used for propaganda.

Look at the chain:

**Physical Operation → Documentation → Media Distribution → Psychological Effect → Political Pressure**

That's not just a cyberattack.

It's not just propaganda.

It's not just espionage.

It's a coordinated attack across multiple domains.

And that's why the old stereotype of the "hacker in a hoodie" is becoming increasingly useless.

Modern threat actors don't necessarily care about staying inside the cyber domain.

If manipulating a person is more effective than exploiting a server, manipulate the person.

If creating a viral narrative is more effective than taking down a website, create the narrative.

If a physical operation can generate more psychological impact than a digital one, use the physical operation.

The domain is irrelevant.

**The objective is what matters.**

## The Forgotten OT/IoT Problem

And then we get to the least glamorous part of cybersecurity.

Which is probably why it's one of the most important.

BIS warns about small industrial and internet-connected systems such as water pumps, heating systems, and IP cameras.

The recommendations aren't exactly revolutionary:

Change default passwords.

Enable MFA where possible.

Limit exposed services and ports.

Update firmware.

Basic security hygiene.

But here's the uncomfortable part.

We love talking about zero-days.

Supply-chain attacks.

APT groups.

Nation-state malware.

Advanced exploitation techniques.

Meanwhile, somewhere on the internet, there may be an industrial controller that has been connected to the public internet for ten years and nobody remembers who configured it.

You don't always need a million-dollar exploit.

Sometimes you just need **something important that somebody forgot about.**

That's the real lesson of exposed OT and IoT.

Complexity isn't always what creates danger.

Sometimes neglect does.

## The Architect's Takeaways

After looking at the report through a cybersecurity and Red Team lens, I think there are seven major conclusions worth taking away:

1. **The human remains one of the most important attack surfaces.** Not because people are stupid, but because humans can be manipulated in ways technical controls cannot completely eliminate.

2. **OSINT is about people as much as infrastructure.** Mapping an organization means understanding its employees, relationships, roles, interests, and access to information.

3. **Social engineering is becoming a long-term operation.** The most effective attacks don't necessarily begin with a malicious link. They can begin with a conversation.

4. **Social media platforms are now part of the information-warfare infrastructure.** Fake accounts, coordinated interactions, and artificial amplification can turn recommendation systems into weapons.

5. **You don't always need to compromise the platform.** Manipulating the environment around an algorithm can be enough to influence what real users see.

6. **A cyberattack can be only one component of a much larger psychological operation.** The technical incident may be temporary, while the narrative created around it continues.

7. **The most dangerous attacks don't necessarily require sophisticated technology.** A neglected device, a compromised account, a trusting employee, and a well-designed social-engineering campaign can become far more powerful when chained together.

## The Battlefield Has Changed

The BIS 2025 Annual Report left me with one conclusion that is difficult to ignore.

The boundaries between **cybersecurity, OSINT, social engineering, espionage, and information warfare are disappearing.**

And maybe those boundaries were never as real as we thought they were.

An attacker doesn't see a clean separation between your network, your employees, your social-media presence, and your public information.

They see one giant attack surface.

They can scan your infrastructure.

They can research your employees.

They can map your relationships.

They can manipulate someone into providing information.

They can use social media to amplify a narrative.

They can use a cyberattack to generate headlines.

And they can combine all of it into a single operation.

That's the real shift.

The target isn't just the server anymore.

**The target is the organization, the people inside it, and the information environment surrounding it.**

The invisible battlefield isn't coming.

It's already here.

`CR1PT0N1C // END OF TRANSMISSION`
