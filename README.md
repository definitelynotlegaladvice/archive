# [Securities Vulnerability] No really... the work does not belong to Aptos.


[Ticket 5135 is not resolved.](https://github.com/aptos-labs/aptos-core/issues/5135)  Since it's not possible to reopen that ticket, here's a new one.

The problem is worse than you think. And closing as "spam" likely made it worse.

From the OP:

<img width="1433" alt="Screen Shot 2023-01-27 at 8 45 40 PM" src="https://user-images.githubusercontent.com/123840750/215296510-973062d1-a261-44ff-8107-9c28b756dead.png">



I think y'all either misunderstand the basics of copyright and licenses, or are attempting to claim credit for the work of a much larger and talented team (over many years).  Likely both.

Either way, the public should know that your project is a recent and shallow fork of Libra-Diem, with no meaningful new features nor architectural changes.

And if you choose not to reveal this, you're in deeper water than you realize:

1. Let's get you up to speed. The owner of a *copyright* is the author who then has the ultimate final rights including the right to decide who can copy. The author can sell these rights to a new owner.  A *license* from the owner defines what it is people can do with a copy, it does not transfer ownership of the property.  An *open source license* (like Apache), allows adaptations to be made to the source and subsequent distribution of copies *under certain conditions*. Licenses are also revocable.<img width="586" alt="Screen Shot 2023-01-27 at 8 49 56 PM" src="https://user-images.githubusercontent.com/123840750/215296586-82630e0f-761a-4128-8c4b-a889cf936f94.png"><img width="586" alt="Screen Shot 2023-01-27 at 8 49 56 PM" src="https://user-images.githubusercontent.com/123840750/215296590-fbae2725-2558-471e-ab3c-f68855695d8c.png">



2. You clearly misunderstand or abuse the Apache license.  The changes Aptos have made to the original code are indeed Aptos' intellectual property.  But only limited to those incremental adaptations.  The original code's ownership has not changed.  So as a fact of law, I'm guessing 95% or more of the code in this repo is not your intellectual property. And you must tell people that.  In fact the Apache license (to the extent you still have one, more below) compels you to do just that. https://www.apache.org/licenses/LICENSE-2.0.html#redistribution

3. You clearly misunderstand or abuse copyrights. All the files in `aptos-core` currently have copyright notices crediting Aptos, in 2022 no less!  Previously the files said "Diem Core Contributors" (which was likely problematic to begin with, since from my recollection that's not an entity). Meanwhile Facebook was the entity that hired, paid and submitted adaptations under the Apache license.  Which makes those contributions authored and owned by Facebook.  As such, the near-entirety of the intellectual property still belongs to them, provided they have not granted all the rights to Libra Association (possibly since the staff was seconded there), and/or subsequently to Silvergate.  God knows where it landed, compliance was pretty catastrophic during my time around the blast radius.

4. Now I point you to the license agreement itself: https://github.com/aptos-labs/aptos-core/blob/main/LICENSE.  If it's not your property you cannot license it.  Full stop.  It's very straightforward: Facebook or Silvergate are the licensors.

5. There is no such thing as a worldwide irrevocable license.  Facebook or Silvergate own the copyright, and as a matter of law, can make and revoke licenses at will.  Revoking rarely happens in open source -- no one wants to be the bad guy.  But it has happened, usually when there have been violations to terms. Given the deception you've put Facebook and Silvergate through at the time of their deal, I think they are well within their right to pull the rug out from under you. And who would fault them?

6. The people Aptos thinks they are licensing it to -- developers, end users, validators -- could also lose the license.  Even if unlikely, this decision is entirely up to Facebook or Silvergate, from now into perpetuity. I wouldn't piss them off, but lord knows you've made enemies.

7. I repeat, Aptos is a shallow fork of Libra-Diem (there's a linear commit history all the way back to the first Libra commit).  The appropriation happened in plain sight, and we see when the copyright notices changed. Willful buffoonery from a founding member: https://github.com/aptos-labs/aptos-core/commit/b1601d23fb157fee4c4932cd093d3809be8094a4

<img width="570" alt="Screen Shot 2023-01-28 at 5 35 14 PM" src="https://user-images.githubusercontent.com/123840750/215296526-e1629235-1e29-4b9a-b126-9e45396507b3.png">

8. It gets a lot worse. If anyone invested with knowledge of the above representations -- that you are the creators of this platform -- that's an easy Section 11 (civil strict liability), maybe Rule 10b (criminal), or even Section 18 (jail time) of the 1933/34 Securities Acts. You only need a single token holder to make that claim in court for you clowns to be completely fucked.



To foreclose the defense of "it was an innocent mistake", let's turn to your track record on business ethics:

1. Mo consults on a blockchain project with Glazers while still at Facebook in violation of his employment agreement.
1. Gets a pre-seed investment from A16Z (eww gross) and proceeds to cut Glazer out. 
1. Gets sued $1B for that. Needs to pay a settlement.
1. Actively solicit engineers from Facebook's staff, in violation of everyone's contract.
1. Wilfully continue to do so when warned by Facebook management.
1. Tries to launch a blockchain without giving any information about the token economics, to the ridicule of the internet.
1. Backpedal and sheepishly reveal the most obscene token distribution anyone can remember: practically all going to themselves and the investors.
1. Commit every possible variation of securities law violations on the launch. (My fave: airdropping tokens to people you KYC'd as American… ballsy)
1. After the FTX implosion: materially misled tokenholders about the character of their relationship. Including that SBF actually didn't put the money in, but got his shares in exchange for "market making".

Given this pattern, "accident" is not going to be a viable defense. You stole property from Facebook and Silvergate, and gave it to yourselves and left some crumbs for the public. Vile.


So if you close this ticket, I'll just keep opening new ones until:
1. Silvergate and Facebook confirm who are the owners
1. They confirm the Apache license is available to you.
1. Update your copyright notices.
1. Update the Apache license to the rightful licensor
1. Properly issue Apache notices of adaptations.
1. Write a blog post detailing all the above,, and pay special notice to who paid for the bulk of the work (not your engineers, they did work for hire).

Before I sign off… some levity.  Savor it.

<img width="586" alt="Screen Shot 2023-01-27 at 8 49 56 PM" src="https://user-images.githubusercontent.com/123840750/215296596-517461eb-a072-4876-aa39-596f6985bb74.png">

