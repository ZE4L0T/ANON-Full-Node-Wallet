# ANON-Full-Node-Wallet
A JAVA based Full Node Wallet for the ANON Network

**Platforms:** Windows, Mac

[Java](https://java.com/en/download/) must be installed.

#### WARNING: Be careful when using this software! It is highly experimental.

#### Always test with small amounts first! It is your responsibility to properly handle your private keys!

#### Do not rely on the wallet.dat file, record your private keys!

#### RECORD YOUR PRIVATE KEYS!!

#### For best security, it is recommended to build the entire Anonymous wallet by yourself, directly from GitHub.

---

### Download the latest release:
https://github.com/anonymousbitcoin/anon-full-node-wallet/releases

The installer is contained in "Assets"

Choose the Windows or Mac installer, depending on your OS.

"ANON_Full_Node_Wallet_Installer_v2.1.1.exe" for Windows

"AnonymousDesktopWallet-2.0.1.app.zip" for Mac

---

### Instructions for Windows installation:



### Notes from ZENCash - Known Issues and Limitations

1. **Issue:** The Anonymous Desktop GUI Wallet is not compatible with applications that modify the ANON `wallet.dat` file. The wallet should not be used
with such applications on the same PC. For instance some distributed exchange applications are known to create watch-only addresses in the
`wallet.dat` file that cause the GUI wallet to display a wrong balance and/or display addresses that do not belong to the wallet.
1. **Limitation:** if two users exchange text messages via the messaging UI TAB and one of them has a system clock, substantially running slow or fast by more than 1 minute, it is possible that this user will see text messages appearing out of order.
1. **Limitation:** if a messaging identity has been created (happens on first click on the messaging UI tab), then replacing the `wallet.dat` or changing the node configuration between mainnet and testnet will make the identity invalid. This will result in a wallet update error. To remove the error the directory `~/.AnonymousDesktopWallet/messaging` may be manually renamed or deleted (when the wallet is stopped). **CAUTION: all messaging history will be lost in this case!**
1. **Limitation:** Wallet encryption has been temporarily disabled in Anonymous due to stability problems. A corresponding issue
[#1552](https://github.com/zcash/zcash/issues/1552) has been opened by the Zcash developers. Correspondingly,
wallet encryption has been temporarily disabled in the Anonymous Desktop GUI Wallet.
The latter needs to be disabled.
1. **Limitation:** The list of transactions does not show all outgoing ones (specifically outgoing Z address
transactions). A corresponding issue [#1438](https://github.com/zcash/zcash/issues/1438) has been opened
for the Zcash developers.
1. **Limitation:** The CPU percentage shown to be taken by anond on Linux is the average for the entire lifetime
of the process. This is not very useful. This will be improved in future versions.
1. **Limitation:** When using a natively compiled wallet version (e.g. `AnonymousDesktopWallet.exe` for Windows) on a
very high resolution monitor with a specifically configured DPI scaling (enlargement) factor to make GUI
elements look larger, the GUI elements of the wallet actually do not scale as expected. To correct this on
Windows you need to right-click on `AnonymousDesktopWallet.exe` and choose option:
```
Properties >> Compatibility >> Override high DPI scaling behavior >> Scaling performed by: (Application)
```



### License
Originally forked from the [BTCP Swing Wallet](https://github.com/BTCPrivate/bitcoin-private-full-node-wallet).

This program is distributed under an MIT License

### Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
