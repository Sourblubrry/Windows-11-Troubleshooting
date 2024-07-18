# Troubleshooting the Blue Screen of Death (BSOD) in Windows 11

## Issue: BSOD Errors

### Steps:
1. Note the Stop Code displayed on the BSOD screen.
2. Boot into Safe Mode:
   - Restart your computer.
   - Press `F8` or `Shift + F8` before the Windows logo appears.
   - Select `Safe Mode`.
3. Check for driver issues:
   - Open Device Manager and update/reinstall problematic drivers.
4. Run memory diagnostics:
   - Press `Win + R` , type `mdsched.exe`, and press `Enter`.
   - Choose `Restart now and check for problems`.
5. Analyze crash dump files:
   - Download and install WinDbg from Microsoft.
   - Open the crash dump file located in `C:\Windows\Minidump\`.
   - Use the `!analyze -v` command to analyze the dump file.
