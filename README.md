valari is  sovergin os that uses no alien code it's completely independent,now have two when i find the other valari.
you may read the code                                                                                                                                             #!/bin/bash
# =============================================================================
# VALARI OS - PROPRIETARY 
# All Rights Reserved / All Rights Reversed
# =============================================================================

cat > LICENSE << 'EOF'
VALARI OS – PROPRIETARY SOFTWARE LICENSE
==========================================
Copyright © 2026 Darrell Lee Stiltner. All Rights Reserved.

1. **NO RIGHTS GRANTED**
   This software and associated documentation files (the "Software") are
   proprietary and confidential. No rights, implied or otherwise, are granted
   to use, copy, modify, merge, publish, distribute, sublicense, or sell
   copies of the Software.

2. **RESTRICTIONS**
   - You may NOT use this Software on any system without explicit written
     permission from the copyright holder.
   - You may NOT copy, modify, or create derivative works based on the
     Software.
   - You may NOT reverse engineer, decompile, or disassemble the Software.
   - You may NOT remove or alter any proprietary notices or labels.

3. **EXTERNAL USE PROHIBITED**
   The Software may not be transferred, disclosed, or otherwise made
   available to any third party without prior written consent.

4. **NO WARRANTY**
   THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
   IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
   FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
   AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
   LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
   FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
   DEALINGS IN THE SOFTWARE.

5. **CONTACT**
   For licensing inquiries, contact: darrell.lee.stiltner@valari.os

   All Rights Reserved. All Rights Reversed. VALARI OS is a trademark of
   Darrell Lee Stiltner.
EOF

# Also create a LICENSE.txt for GitHub
cp LICENSE LICENSE.txt

# Create a NOTICE file
cat > NOTICE << 'EOF'
VALARI OS
Copyright © 2026 Darrell Lee Stiltner

This software is proprietary and confidential.
Unauthorized use, copying, or distribution is prohibited.

For licensing: darrell.lee.stiltner@valari.os
EOF

# Create a README license section
cat >> README.md << 'EOF'

## 📜 License

**PROPRIETARY – ALL RIGHTS RESERVED**

This software is the exclusive property of Darrell Lee Stiltner.
Unauthorized use, reproduction, or distribution is strictly prohibited.

See the [LICENSE](LICENSE) file for complete terms.

© 2026 Darrell Lee Stiltner. All rights reserved. All rights reversed.
EOF

echo "✅ Proprietary license files created:"
echo "   - LICENSE"
echo "   - LICENSE.txt"
echo "   - NOTICE"
echo ""
echo "📋 Next steps:"
echo "   git add LICENSE LICENSE.txt NOTICE"
echo "   git commit -m \"Add proprietary license - All Rights Reserved\""
echo "   git push"
echo ""
echo "🔷 RURI SAYS: \"Your code. Your rules. All rights reversed.\""
