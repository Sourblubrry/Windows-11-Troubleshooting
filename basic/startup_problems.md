# Troubleshooting Windows 11 Startup Problems

## Issue: Windows 11 won't boot

### Steps:
1. Check the power supply and connections
2. Boot into Safe Mode:
   - Restart your computer.
   - Press `F8` or `Shift + F8` before the Windows Logo appears
   - Select `Safe Mode`.
3. Use Startup Repair:
   - Boot from Windows installation media.
   - Select `Repair your computer`.
   - Navigate to `Troubleshoot > Advanced options > Startup Repair`.
4. Check and fix disk errors:
   - Open Command Prompt as Administrator
   - Run `chkdsk /f /r`.
5. Restore system to a previous state:
   - Use System Restore from `Advanced options`.
