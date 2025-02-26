# homebrew-selfuse
selfuse homebrew tap
```bash
# add tap
brew tap liuxhit/selfuse
brew update
brew search maven
```

## maven@3.6
https://github.com/Homebrew/homebrew-core/pull/86192#issuecomment-931509947
```bash
brew install liuxhit/selfuse/maven@3.6
# for debug:
# HOMEBREW_DEVELOPER=1 brew install liuxhit/selfuse/maven@3.6 --verbose --debug 2>&1 | tee -a ./brew_install_mvn36.log
```
```text
==> maven@3.6
maven@3.6 is keg-only, which means it was not symlinked into /opt/homebrew,
because this is an alternate version of another formula.

If you need to have maven@3.6 first in your PATH, run:
  echo 'export PATH="/opt/homebrew/opt/maven@3.6/bin:$PATH"' >> ~/.zshrc
==> openjdk@11
For the system Java wrappers to find this JDK, symlink it with
  sudo ln -sfn /opt/homebrew/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-11.jdk

openjdk@11 is keg-only, which means it was not symlinked into /opt/homebrew,
because this is an alternate version of another formula.

If you need to have openjdk@11 first in your PATH, run:
  echo 'export PATH="/opt/homebrew/opt/openjdk@11/bin:$PATH"' >> ~/.zshrc

For compilers to find openjdk@11 you may need to set:
  export CPPFLAGS="-I/opt/homebrew/opt/openjdk@11/include"
==> wireshark
This formula only installs the command-line utilities by default.

Install Wireshark.app with Homebrew Cask:
  brew install --cask wireshark

If your list of available capture interfaces is empty
(default macOS behavior), install ChmodBPF:
  brew install --cask wireshark-chmodbpf
```
