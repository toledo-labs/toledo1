Commercial Software License

This Commercial Software License Agreement (this “Agreement”) is a legal agreement between [Customer] (“You” or “Licensee”) and [Toledo Systems] (“Licensor”) made as of [purchase date] (the “Effective Date”).

RECITALS

A. Licensor, through its development of certain software (the “Software”), wishes to grant a commercial license to Licensee to use the Software in accordance with certain terms, conditions, and obligations set forth herein; and

B. Licensee desires to obtain such a license and is willing to be bound by the terms, conditions, and obligations of this Agreement in order to achieve the mutual purposes represented herein.

NOW THEREFORE, in consideration of the respective covenants, promises and mutual agreements herein contained and other valuable consideration, the receipt and sufficiency of which are hereby acknowledged, the parties hereto agree as follows:

License Grant. Licensor hereby grants Licensee a non-exclusive and non-transferable license to commercially use the Software according to the following terms and conditions.

Detail. Licensee may not copy, transfer, sublicense, market, or otherwise distribute the Software in any manner that does not comply with this Agreement. Licensee may use the Software for its own commercial purposes, provided that such purposes shall not be in violation of any applicable laws. Licensee shall not allow any other person or entity to gain access to or utilize the Software or any part of the Software.

Intellectual Property Rights. The Software is owned by Licensor, and all intellectual property rights therein are and shall continue to be the exclusive property of Licensor. This Agreement in no way grants to Licensee intellectual property rights or any other ownership rights to the Software or any other derivative works created therefrom. 

Warranty Disclaimer. Licensor makes no promises, warranties, or representations about the content, quality, functionality, or performance of the Software. Licensor expressly disclaims all warranties of any type, either express or implied, including without limitation any implied warranties of merchantability, non-infringement, title, or fitness for a particular purpose.

Indemnification. Licensee agrees to indemnify and hold Licensor harmless from any and all losses, costs, damages, or expenses, which an indemnified party may suffer, incur, pay, or be obligated to pay due to Licensee’s breach or violation of this Agreement.

Limitation of Liability. In no event shall Licensor or any of its licensors be liable to Licensee or any other person or entity for any indirect, incidental, special or consequential damages whatsoever, including but not limited to any lost profits, lost savings, lost data, or other incidental or consequential damages by any person or entity that arises out of or is related to the use of the Software.

Termination. This Agreement is effective until terminated by either party. If Licensee breaches any of the terms or conditions of this Agreement, Licensor may terminate this Agreement at any time. Upon termination, Licensee shall immediately cease all use of the Software and destroy or return to Licensor all copies of the Software in Licensee’s possession or control.

Entire Agreement. This Agreement constitutes the entire agreement between the parties with respect to the use of the Software and supersedes any and all prior written or oral representations, understandings, and agreements between the parties. Any subsequent modifications or amendments to this Agreement shall be in writing and signed by both parties.

Governing Law. This Agreement shall be governed in all respects by the laws of [Florida].

IN WITNESS WHEREOF, the parties hereto have executed this Agreement on the date and year first above written.

Licensor: [Toledo Systems LLC: toledo@toledosystems.net]

Licensee: [Customer]

Thank you for downloading Toledo1
Please consider a donation so this research may continue
Bitcoin: https://toledolabs.io/pay/
Paypal: toledo@toledosystems.net

#### Toledo1 Install instructions

1. (Optional) Add your API key to the operating system environment with name "OPENAI_API_KEY" 

   Example: add the below line into the user ~/.bashrc with a text editor:
   
   ```bash
   export OPENAI_API_KEY="API KEY from your inference server"
   ```  
    
   Save ~/.bashrc then exit and source it:
   
   ```bash
   $ source ~/.bashrc
   ```   
   
2. Install Toledo1 

   ```bash
   # Do not run with sudo!
   $ ./install_toledo1_with_flatpak.sh
   ```
   
3. Search for Toledo1 and pin it to the taskbar
4. Launch Toledo1 by clicking on its icon

#### Remove Toledo1 instructions

1. Remove Toledo1
   ```bash
   $ flatpak uninstall com.toledo1.Toledo1
   ```
