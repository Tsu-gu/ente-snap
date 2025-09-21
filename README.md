This snap is built using the provided .deb file (The official flatpak is the same)

Things work but when launching via the terminal these errors can be seen. I tried connecting the password-manager-service plug but it didn't fix it
```
strict mode: missing type "object" for keyword "properties" at "#/properties/windowBounds" (strictTypes)
Gtk-Message: 12:49:13.463: Not loading module "atk-bridge": The functionality is provided by GTK natively. Please try to not load it.
[3444:0921/124913.664500:ERROR:content/browser/zygote_host/zygote_host_impl_linux.cc:283] Failed to adjust OOM score of renderer with pid 3557: Permission denied (13)
[3557:0921/124913.901367:ERROR:ui/gfx/linux/gbm_wrapper.cc:79] Failed to get fd for plane.: No such file or directory (2)
[3557:0921/124913.903158:ERROR:ui/gfx/linux/gbm_wrapper.cc:261] Failed to export buffer to dma_buf: No such file or directory (2)
. . .
Checking for beta autoupdate feature for deb/rpm distributions
Found package-type: deb
(node:3444) [DEP0180] DeprecationWarning: fs.Stats constructor is deprecated.
(Use `ente --trace-deprecation ...` to show where the warning was created)
Error occurred in handler for 'masterKeyFromSafeStorage': Error: Error while decrypting the ciphertext provided to safeStorage.decryptString.
    at masterKeyFromSafeStorage (/snap/ente-tsugu/4/opt/ente/resources/app.asar/app/main/services/store.js:40:31)
    at /snap/ente-tsugu/4/opt/ente/resources/app.asar/app/main/ipc.js:56:98
    at Session.<anonymous> (node:electron/js2c/browser_init:2:107040)
    at Session.emit (node:events:518:28)
Error occurred in handler for 'masterKeyFromSafeStorage': Error: Error while decrypting the ciphertext provided to safeStorage.decryptString.
    at masterKeyFromSafeStorage (/snap/ente-tsugu/4/opt/ente/resources/app.asar/app/main/services/store.js:40:31)
    at /snap/ente-tsugu/4/opt/ente/resources/app.asar/app/main/ipc.js:56:98
    at Session.<anonymous> (node:electron/js2c/browser_init:2:107040)
    at Session.emit (node:events:518:28)
[3557:0921/124918.478846:ERROR:ui/gl/gl_surface_presentation_helper.cc:260] GetVSyncParametersIfAvailable() failed for 1 times!
. . .
```
