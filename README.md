![Ripple](/images/ripple.png)

#The World’s Fastest and Most Secure Payment System

**What is Ripple?**

Ripple is the open-source, distributed payment protocol that enables instant
payments with low fees, no chargebacks, and currency flexibility (for example
dollars, yen, euros, bitcoins, or even loyalty points). Businesses of any size
can easily build payment solutions such as banking or remittance apps, and
accelerate the movement of money. Ripple enables the world to move value the
way it moves information on the Internet.

![Ripple Network](images/network.png)

**What is a Gateway?**

Ripple works with gateways: independent businesses which hold customer
deposits in various currencies such as U.S. dollars (USD) or Euros (EUR),
in exchange for providing cryptographically-signed issuances that users can
send and trade with one another in seconds on the Ripple network. Within the
protocol, exchanges between multiple currencies can occur atomically without
any central authority to monitor them. Later, customers can withdraw their
Ripple balances from the gateways that created those issuances.

**How do Ripple payments work?**

A sender specifies the amount and currency the recipient should receive and
Ripple automatically converts the sender’s available currencies using the
distributed order books integrated into the Ripple protocol. Independent third
parties acting as  market makers provide liquidity in these order books.

Ripple uses a pathfinding algorithm that considers currency pairs when
converting from the source to the destination currency. This algorithm searches
for a series of currency swaps that gives the user the lowest cost. Since
anyone can participate as a market maker, market forces drive fees to the
lowest practical level.

**What can you do with Ripple?**

The protocol is entirely open-source and the network’s shared ledger is public
information, so no central authority prevents anyone from participating. Anyone
can become a market maker, create a wallet or a gateway, or monitor network
behavior. Competition drives down spreads and fees, making the network useful
to everyone.


###Key Protocol Features
1. XRP is Ripple’s native [cryptocurrency]
(http://en.wikipedia.org/wiki/Cryptocurrency) with a fixed supply that
decreases slowly over time, with no mining. XRP acts as a bridge currency, and
pays for transaction fees that protect the network against spam.
![XRP as a bridge currency](/images/vehicle_currency.png)

2. Pathfinding discovers cheap and efficient payment paths through multiple
[order books](https://www.ripplecharts.com) allowing anyone to [trade](https://www.rippletrade.com) anything. When two accounts aren’t linked by relationships of trust, the Ripple pathfinding engine considers intermediate links and order books to produce a set of possible paths the transaction can take. When the payment is processed, the liquidity along these paths is iteratively consumed in best-first order.
![Pathfinding from Dollars to Euro](/images/pathfinding.png)

3. [Consensus](https://www.youtube.com/watch?v=pj1QVb1vlC0) confirms
transactions in an atomic fashion, without mining, ensuring efficient use of
resources.

[transact]: https://ripple.com/files/ripple-FIs.pdf
[build]:    https://ripple.com/build/

[transact.png]:   /images/transact.png
[build.png]:      /images/build.png
[contribute.png]: /images/contribute.png

###Join The Ripple Community
|![Transact][transact.png]|![Build][build.png]|![Contribute][contribute.png]|
|:-----------------------:|:-----------------:|:---------------------------:|
|[Transact on the fastest payment infrastructure][transact]|[Build Imaginative Apps][build]|Contribute to the Ripple Protocol Implementation|

#rippled - Ripple P2P server

##[![Build Status](https://travis-ci.org/ripple/rippled.png?branch=develop)](https://travis-ci.org/ripple/rippled)

This is the repository for Ripple's `rippled`, reference P2P server.

###Build instructions:
* https://ripple.com/wiki/Rippled_build_instructions

###Setup instructions:
* https://ripple.com/wiki/Rippled_setup_instructions

###Issues
* https://ripplelabs.atlassian.net/browse/RIPD

### Repository Contents

#### ./bin
Scripts and data files for Ripple integrators.

#### ./build
Intermediate and final build outputs.

#### ./Builds
Platform or IDE-specific project files.

#### ./doc
Documentation and example configuration files.

#### ./src
Source code directory. Some of the directories contained here are
external repositories inlined via git-subtree, see the corresponding
README for more details.

#### ./test
Javascript / Mocha tests.

## License

Apache License
                           Version 2.0, January 2004
                        https://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "[]"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright 2019 Rolando Gopez Lacuata

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       https://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

###For more information:
* Ripple Wiki - https://ripple.com/wiki/
* Ripple Primer - https://ripple.com/ripple_primer.pdf
* Ripple Primer (Market Making) - https://ripple.com/ripple-mm.pdf
* Ripple Gateway Primer - https://ripple.com/ripple-gateways.pdf
* Consensus - https://wiki.ripple.com/Consensus

- - -

Copyright © 2015, Ripple Labs. All rights reserved.

Portions of this document, including but not limited to the Ripple logo, images
and image templates are the property of Ripple Labs and cannot be copied or
used without permission.
