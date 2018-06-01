# Vulture report for qutebrowser

We used vulture (https://github.com/jendrikseipp/vulture) to search
for unused code in your project. You can find the report below. It 
would be great if you could give us feedback about which items are 
actually used or unused. This would allow us to improve vulture and
ideally it also helps you to remove obsolete code or even find typos 
and bugs.

### Command

```
vulture . --exclude tests/
```

### Raw Results

```
qutebrowser/qutebrowser/app.py:81: unused import 'utilcmds' (90% confidence)
qutebrowser/qutebrowser/app.py:619: unused function 'restart_cmd' (60% confidence)
qutebrowser/qutebrowser/app.py:911: unused function 'eventFilter' (60% confidence)
qutebrowser/qutebrowser/browser/adblock.py:162: unused function 'adblock_update' (60% confidence)
qutebrowser/qutebrowser/browser/browsertab.py:734: unused attribute 'posted' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:226: unused function 'tab_close' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:248: unused function 'tab_pin' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:367: unused function 'reloadpage' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:439: unused function 'printpage' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:516: unused function 'tab_take' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:569: unused function 'tab_detach' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:687: unused function 'scroll_px' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:740: unused function 'scroll_to_perc' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:771: unused function 'scroll_to_anchor' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:780: unused function 'scroll_page' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:899: unused function 'zoom_in' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:914: unused function 'zoom_out' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1007: unused function 'tab_prev' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1124: unused function 'tab_focus' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1163: unused function 'tab_move' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1309: unused function 'quickmark_save' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1315: unused function 'quickmark_load' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1333: unused function 'quickmark_del' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1356: unused function 'bookmark_add' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1396: unused function 'bookmark_load' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1448: unused function 'toggle_inspector' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1523: unused function 'view_source' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1545: unused function 'debug_dump_page' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1581: unused function 'show_help' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1656: unused function 'open_editor' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1706: unused function 'click_element' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1812: unused function 'search_next' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:1846: unused function 'search_prev' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:2037: unused function 'debug_webaction' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:2112: unused function 'fake_key' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:2144: unused function 'debug_clear_ssl_errors' (60% confidence)
qutebrowser/qutebrowser/browser/commands.py:2150: unused function 'edit_url' (60% confidence)
qutebrowser/qutebrowser/browser/downloads.py:977: unused function 'download_cancel' (60% confidence)
qutebrowser/qutebrowser/browser/downloads.py:1003: unused function 'download_delete' (60% confidence)
qutebrowser/qutebrowser/browser/downloads.py:1048: unused function 'download_retry' (60% confidence)
qutebrowser/qutebrowser/browser/downloads.py:1083: unused function 'download_remove' (60% confidence)
qutebrowser/qutebrowser/browser/downloads.py:1123: unused function 'headerData' (60% confidence)
qutebrowser/qutebrowser/browser/hints.py:917: unused function 'follow_hint' (60% confidence)
qutebrowser/qutebrowser/browser/history.py:336: unused function 'debug_dump_history' (60% confidence)
qutebrowser/qutebrowser/browser/mouse.py:49: unused function 'eventFilter' (60% confidence)
qutebrowser/qutebrowser/browser/mouse.py:214: unused function 'eventFilter' (60% confidence)
qutebrowser/qutebrowser/browser/network/pac.py:102: unused function 'dnsResolve' (60% confidence)
qutebrowser/qutebrowser/browser/network/pac.py:120: unused function 'myIpAddress' (60% confidence)
qutebrowser/qutebrowser/browser/network/proxy.py:57: unused function 'queryProxy' (60% confidence)
qutebrowser/qutebrowser/browser/pdfjs.py:201: unused function 'is_available' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:191: unused function 'qute_bookmarks' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:206: unused function 'qute_tabs' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:248: unused function 'qute_history' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:273: unused function 'qute_javascript' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:287: unused function 'qute_pyeval' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:294: unused function 'qute_spawn_output' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:301: unused function 'qute_version' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:311: unused function 'qute_plainlog' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:330: unused function 'qute_log' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:350: unused function 'qute_gpl' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:356: unused function 'qute_help' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:415: unused function 'qute_backend_warning' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:447: unused function 'qute_settings' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:459: unused function 'qute_bindings' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:475: unused function 'qute_back' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:487: unused function 'qute_configdiff' (60% confidence)
qutebrowser/qutebrowser/browser/qutescheme.py:502: unused function 'qute_pastebin_version' (60% confidence)
qutebrowser/qutebrowser/browser/webengine/interceptor.py:44: unused function 'interceptRequest' (60% confidence)
qutebrowser/qutebrowser/browser/webengine/webenginequtescheme.py:38: unused function 'requestStarted' (60% confidence)
qutebrowser/qutebrowser/browser/webengine/webview.py:57: unused function 'createWindow' (60% confidence)
qutebrowser/qutebrowser/browser/webengine/webview.py:209: unused function 'certificateError' (60% confidence)
qutebrowser/qutebrowser/browser/webengine/webview.py:285: unused function 'javaScriptConsoleMessage' (60% confidence)
qutebrowser/qutebrowser/browser/webengine/webview.py:294: unused function 'acceptNavigationRequest' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/mhtml.py:567: unused attribute 'last_used_directory' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/network/networkreply.py:80: unused function 'readData' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/network/networkreply.py:97: unused function 'isRunning' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/network/networkreply.py:132: unused function 'readData' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/network/networkreply.py:139: unused function 'isRunning' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/network/networkreply.py:156: unused function 'readData' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/network/webkitqutescheme.py:59: unused function 'qute_pdfjs' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:65: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:90: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:103: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:112: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:123: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:138: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:145: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:173: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:180: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:191: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:198: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/rfc6266.py:208: unused variable 'grammar' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/webkithistory.py:42: unused function 'addHistoryEntry' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/webpage.py:138: unused attribute 'baseUrl' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/webpage.py:205: unused attribute 'fileNames' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/webpage.py:424: unused function 'supportsExtension' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/webpage.py:475: unused function 'javaScriptConsoleMessage' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/webpage.py:480: unused function 'acceptNavigationRequest' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/webview.py:159: unused function 'createWindow' (60% confidence)
qutebrowser/qutebrowser/browser/webkit/webview.py:218: unused function 'contextMenuEvent' (60% confidence)
qutebrowser/qutebrowser/completion/completiondelegate.py:168: unused attribute 'clip' (60% confidence)
qutebrowser/qutebrowser/completion/completiondelegate.py:236: unused attribute 'backgroundColor' (60% confidence)
qutebrowser/qutebrowser/completion/completionwidget.py:230: unused function 'completion_item_focus' (60% confidence)
qutebrowser/qutebrowser/completion/completionwidget.py:391: unused function 'completion_item_del' (60% confidence)
qutebrowser/qutebrowser/completion/completionwidget.py:400: unused function 'completion_item_yank' (60% confidence)
qutebrowser/qutebrowser/completion/models/histcategory.py:105: unused function 'removeRows' (60% confidence)
qutebrowser/qutebrowser/completion/models/listcategory.py:64: unused function 'lessThan' (60% confidence)
qutebrowser/qutebrowser/config/configcommands.py:191: unused function 'config_cycle' (60% confidence)
qutebrowser/qutebrowser/config/configcommands.py:239: unused function 'config_unset' (60% confidence)
qutebrowser/qutebrowser/config/configcommands.py:264: unused function 'config_source' (60% confidence)
qutebrowser/qutebrowser/config/configcommands.py:286: unused function 'config_edit' (60% confidence)
qutebrowser/qutebrowser/config/configcommands.py:310: unused function 'config_write_py' (60% confidence)
qutebrowser/qutebrowser/config/configfiles.py:334: unused attribute 'datadir' (60% confidence)
qutebrowser/qutebrowser/config/configfiles.py:359: unused function 'load_autoconfig' (60% confidence)
qutebrowser/qutebrowser/config/configfiles.py:527: unused attribute 'c' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:396: unused class 'UniqueCharString' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:639: unused class 'BoolAsk' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:739: unused class 'Float' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:761: unused class 'Perc' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:786: unused class 'PercOrInt' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:875: unused class 'ColorSystem' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:896: unused class 'QtColor' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:920: unused class 'QssColor' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:997: unused class 'FontFamily' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1019: unused class 'QtFont' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1084: unused class 'Regex' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1249: unused class 'File' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1279: unused class 'Directory' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1302: unused class 'FormatString' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1326: unused class 'ShellCommand' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1356: unused class 'Proxy' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1398: unused class 'SearchEngineUrl' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1426: unused class 'FuzzyUrl' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1452: unused class 'Padding' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1469: unused class 'Encoding' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1484: unused class 'Position' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1501: unused class 'TextAlignment' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1517: unused class 'VerticalPosition' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1526: unused class 'Url' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1542: unused class 'SessionName' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1555: unused class 'SelectOnRemove' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1576: unused class 'ConfirmQuit' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1611: unused class 'NewTabPosition' (60% confidence)
qutebrowser/qutebrowser/config/configtypes.py:1624: unused class 'TimestampTemplate' (60% confidence)
qutebrowser/qutebrowser/keyinput/macros.py:44: unused function 'record_macro_command' (60% confidence)
qutebrowser/qutebrowser/keyinput/macros.py:69: unused function 'run_macro_command' (60% confidence)
qutebrowser/qutebrowser/keyinput/modeman.py:260: unused function 'enter_mode' (60% confidence)
qutebrowser/qutebrowser/keyinput/modeman.py:305: unused function 'leave_current_mode' (60% confidence)
qutebrowser/qutebrowser/mainwindow/prompt.py:368: unused function 'prompt_accept' (60% confidence)
qutebrowser/qutebrowser/mainwindow/prompt.py:392: unused function 'prompt_open_download' (60% confidence)
qutebrowser/qutebrowser/mainwindow/prompt.py:411: unused function 'prompt_item_focus' (60% confidence)
qutebrowser/qutebrowser/mainwindow/prompt.py:425: unused function 'prompt_yank' (60% confidence)
qutebrowser/qutebrowser/mainwindow/statusbar/bar.py:262: unused function 'color_flags' (60% confidence)
qutebrowser/qutebrowser/mainwindow/statusbar/command.py:116: unused function 'set_cmd_text_command' (60% confidence)
qutebrowser/qutebrowser/mainwindow/statusbar/command.py:199: unused function 'edit_command' (60% confidence)
qutebrowser/qutebrowser/mainwindow/statusbar/url.py:91: unused function 'urltype' (60% confidence)
qutebrowser/qutebrowser/mainwindow/tabwidget.py:572: unused function 'tabSizeHint' (60% confidence)
qutebrowser/qutebrowser/misc/backendproblem.py:263: unused import 'QtWebKitWidgets' (90% confidence)
qutebrowser/qutebrowser/misc/backendproblem.py:275: unused import 'QtWebEngineWidgets' (90% confidence)
qutebrowser/qutebrowser/misc/earlyinit.py:136: unused import 'PyQt5' (90% confidence)
qutebrowser/qutebrowser/misc/guiprocess.py:108: unused attribute 'spawn_output' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:51: unused function 'rl_backward_char' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:63: unused function 'rl_forward_char' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:75: unused function 'rl_backward_word' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:87: unused function 'rl_forward_word' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:99: unused function 'rl_beginning_of_line' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:111: unused function 'rl_end_of_line' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:123: unused function 'rl_unix_line_discard' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:137: unused function 'rl_kill_line' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:176: unused function 'rl_unix_word_rubout' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:186: unused function 'rl_unix_filename_rubout' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:195: unused function 'rl_backward_kill_word' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:210: unused function 'rl_kill_word' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:224: unused function 'rl_yank' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:236: unused function 'rl_delete_char' (60% confidence)
qutebrowser/qutebrowser/misc/readline.py:248: unused function 'rl_backward_delete_char' (60% confidence)
qutebrowser/qutebrowser/misc/savemanager.py:181: unused function 'save_command' (60% confidence)
qutebrowser/qutebrowser/misc/sessions.py:459: unused function 'session_load' (60% confidence)
qutebrowser/qutebrowser/misc/sessions.py:500: unused function 'session_save' (60% confidence)
qutebrowser/qutebrowser/misc/sessions.py:541: unused function 'session_delete' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:45: unused function 'later' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:75: unused function 'repeat' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:91: unused function 'run_with_count' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:107: unused function 'message_error' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:117: unused function 'message_info' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:130: unused function 'message_warning' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:146: unused function 'debug_crash' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:161: unused function 'debug_all_objects' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:168: unused function 'debug_cache_stats' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:216: unused function 'debug_trace' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:232: unused function 'debug_pyeval' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:261: unused attribute 'pyeval_output' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:270: unused function 'debug_set_fake_clipboard' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:278: unused attribute 'log_clipboard' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:280: unused attribute 'fake_clipboard' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:283: unused function 'repeat_command' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:300: unused function 'log_capacity' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:313: unused function 'debug_log_level' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:327: unused function 'debug_log_filter' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:351: unused function 'window_only' (60% confidence)
qutebrowser/qutebrowser/misc/utilcmds.py:365: unused function 'nop' (60% confidence)
qutebrowser/qutebrowser/resources.py:5471: unused function 'qCleanupResources' (60% confidence)
qutebrowser/qutebrowser/utils/debug.py:34: unused function 'log_events' (60% confidence)
qutebrowser/qutebrowser/utils/debug.py:49: unused function 'log_signals' (60% confidence)
qutebrowser/qutebrowser/utils/jinja.py:64: unused function 'get_source' (60% confidence)
qutebrowser/qutebrowser/utils/log.py:487: unused function 'filter' (60% confidence)
qutebrowser/qutebrowser/utils/log.py:508: unused function 'filter' (60% confidence)
qutebrowser/qutebrowser/utils/log.py:629: unused attribute 'log_color' (60% confidence)
qutebrowser/qutebrowser/utils/log.py:631: unused attribute 'log_color' (60% confidence)
qutebrowser/qutebrowser/utils/message.py:206: unused variable 'log_stack' (100% confidence)
qutebrowser/qutebrowser/utils/message.py:256: unused variable 'log_stack' (100% confidence)
qutebrowser/qutebrowser/utils/message.py:267: unused variable 'log_stack' (100% confidence)
qutebrowser/qutebrowser/utils/qtutils.py:70: unused attribute 'qt_errno' (60% confidence)
qutebrowser/qutebrowser/utils/qtutils.py:72: unused attribute 'qt_errno' (60% confidence)
qutebrowser/qutebrowser/utils/qtutils.py:265: unused function 'fileno' (60% confidence)
qutebrowser/qutebrowser/utils/qtutils.py:286: unused property 'closed' (60% confidence)
qutebrowser/qutebrowser/utils/qtutils.py:298: unused function 'readable' (60% confidence)
qutebrowser/scripts/asciidoc2html.py:273: unused attribute 'use_color' (60% confidence)
qutebrowser/scripts/dev/get_coredumpctl_traces.py:45: unused variable 'uid' (60% confidence)
qutebrowser/scripts/dev/get_coredumpctl_traces.py:46: unused variable 'gid' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/config.py:41: unused variable 'msgs' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/config.py:46: unused variable 'priority' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/config.py:49: unused function 'visit_attribute' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/modeline.py:34: unused variable 'msgs' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/modeline.py:38: unused variable 'priority' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/modeline.py:40: unused function 'process_module' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/openencoding.py:34: unused variable 'msgs' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/openencoding.py:39: unused function 'visit_call' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/settrace.py:32: unused variable 'msgs' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/settrace.py:35: unused variable 'priority' (60% confidence)
qutebrowser/scripts/dev/pylint_checkers/qute_pylint/settrace.py:37: unused function 'visit_call' (60% confidence)
qutebrowser/scripts/dev/src2asciidoc.py:64: unused function '_get_default_metavar_for_optional' (60% confidence)
qutebrowser/scripts/dev/src2asciidoc.py:68: unused function '_get_default_metavar_for_positional' (60% confidence)
qutebrowser/scripts/dev/src2asciidoc.py:72: unused function '_metavar_formatter' (60% confidence)
qutebrowser/scripts/importer.py:295: unused attribute 'row_factory' (60% confidence)
qutebrowser/scripts/utils.py:52: unused variable 'bg_colors' (60% confidence)
```

### False positives

Source: https://github.com/qutebrowser/qutebrowser/blob/master/scripts/dev/run_vulture.py

```
qutebrowser.config.configcommands.ConfigCommands.set
qutebrowser.config.configcommands.ConfigCommands.bind
qutebrowser.config.configcommands.ConfigCommands.unbind
qutebrowser.config.configcommands.ConfigCommands.config_cycle
qutebrowser.config.configcommands.ConfigCommands.config_unset
qutebrowser.config.configcommands.ConfigCommands.config_clear
qutebrowser.config.configcommands.ConfigCommands.config_source
qutebrowser.config.configcommands.ConfigCommands.config_edit
qutebrowser.config.configcommands.ConfigCommands.config_write_py
qutebrowser.browser.urlmarks.QuickmarkManager.quickmark_add
qutebrowser.browser.downloads.DownloadModel.download_cancel
qutebrowser.browser.downloads.DownloadModel.download_delete
qutebrowser.browser.downloads.DownloadModel.download_open
qutebrowser.browser.downloads.DownloadModel.download_retry
qutebrowser.browser.downloads.DownloadModel.download_clear
qutebrowser.browser.downloads.DownloadModel.download_remove
qutebrowser.browser.adblock.HostBlocker.adblock_update
qutebrowser.browser.history.WebHistory.clear
qutebrowser.browser.history.WebHistory.debug_dump_history
qutebrowser.keyinput.modeman.ModeManager.enter_mode
qutebrowser.keyinput.modeman.ModeManager.leave_current_mode
qutebrowser.keyinput.modeman.ModeManager.clear_keychain
qutebrowser.mainwindow.prompt.PromptContainer.prompt_accept
qutebrowser.mainwindow.prompt.PromptContainer.prompt_open_download
qutebrowser.mainwindow.prompt.PromptContainer.prompt_item_focus
qutebrowser.mainwindow.prompt.PromptContainer.prompt_yank
qutebrowser.completion.completionwidget.CompletionView.completion_item_focus
qutebrowser.completion.completionwidget.CompletionView.completion_item_del
qutebrowser.completion.completionwidget.CompletionView.completion_item_yank
qutebrowser.browser.commands.CommandDispatcher.tab_close
qutebrowser.browser.commands.CommandDispatcher.tab_pin
qutebrowser.browser.commands.CommandDispatcher.openurl
qutebrowser.browser.commands.CommandDispatcher.reloadpage
qutebrowser.browser.commands.CommandDispatcher.stop
qutebrowser.browser.commands.CommandDispatcher.printpage
qutebrowser.browser.commands.CommandDispatcher.tab_clone
qutebrowser.browser.commands.CommandDispatcher.tab_take
qutebrowser.browser.commands.CommandDispatcher.tab_give
qutebrowser.browser.commands.CommandDispatcher.tab_detach
qutebrowser.browser.commands.CommandDispatcher.back
qutebrowser.browser.commands.CommandDispatcher.forward
qutebrowser.browser.commands.CommandDispatcher.navigate
qutebrowser.browser.commands.CommandDispatcher.scroll_px
qutebrowser.browser.commands.CommandDispatcher.scroll
qutebrowser.browser.commands.CommandDispatcher.scroll_to_perc
qutebrowser.browser.commands.CommandDispatcher.scroll_to_anchor
qutebrowser.browser.commands.CommandDispatcher.scroll_page
qutebrowser.browser.commands.CommandDispatcher.yank
qutebrowser.browser.commands.CommandDispatcher.zoom_in
qutebrowser.browser.commands.CommandDispatcher.zoom_out
qutebrowser.browser.commands.CommandDispatcher.zoom
qutebrowser.browser.commands.CommandDispatcher.tab_only
qutebrowser.browser.commands.CommandDispatcher.undo
qutebrowser.browser.commands.CommandDispatcher.tab_prev
qutebrowser.browser.commands.CommandDispatcher.tab_next
qutebrowser.browser.commands.CommandDispatcher.buffer
qutebrowser.browser.commands.CommandDispatcher.tab_focus
qutebrowser.browser.commands.CommandDispatcher.tab_move
qutebrowser.browser.commands.CommandDispatcher.spawn
qutebrowser.browser.commands.CommandDispatcher.home
qutebrowser.browser.commands.CommandDispatcher.quickmark_save
qutebrowser.browser.commands.CommandDispatcher.quickmark_load
qutebrowser.browser.commands.CommandDispatcher.quickmark_del
qutebrowser.browser.commands.CommandDispatcher.bookmark_add
qutebrowser.browser.commands.CommandDispatcher.bookmark_load
qutebrowser.browser.commands.CommandDispatcher.bookmark_del
qutebrowser.browser.commands.CommandDispatcher.follow_selected
qutebrowser.browser.commands.CommandDispatcher.toggle_inspector
qutebrowser.browser.commands.CommandDispatcher.download
qutebrowser.browser.commands.CommandDispatcher.view_source
qutebrowser.browser.commands.CommandDispatcher.debug_dump_page
qutebrowser.browser.commands.CommandDispatcher.history
qutebrowser.browser.commands.CommandDispatcher.show_help
qutebrowser.browser.commands.CommandDispatcher.messages
qutebrowser.browser.commands.CommandDispatcher.open_editor
qutebrowser.browser.commands.CommandDispatcher.insert_text
qutebrowser.browser.commands.CommandDispatcher.click_element
qutebrowser.browser.commands.CommandDispatcher.search
qutebrowser.browser.commands.CommandDispatcher.search_next
qutebrowser.browser.commands.CommandDispatcher.search_prev
qutebrowser.browser.commands.CommandDispatcher.move_to_next_line
qutebrowser.browser.commands.CommandDispatcher.move_to_prev_line
qutebrowser.browser.commands.CommandDispatcher.move_to_next_char
qutebrowser.browser.commands.CommandDispatcher.move_to_prev_char
qutebrowser.browser.commands.CommandDispatcher.move_to_end_of_word
qutebrowser.browser.commands.CommandDispatcher.move_to_next_word
qutebrowser.browser.commands.CommandDispatcher.move_to_prev_word
qutebrowser.browser.commands.CommandDispatcher.move_to_start_of_line
qutebrowser.browser.commands.CommandDispatcher.move_to_end_of_line
qutebrowser.browser.commands.CommandDispatcher.move_to_start_of_next_block
qutebrowser.browser.commands.CommandDispatcher.move_to_start_of_prev_block
qutebrowser.browser.commands.CommandDispatcher.move_to_end_of_next_block
qutebrowser.browser.commands.CommandDispatcher.move_to_end_of_prev_block
qutebrowser.browser.commands.CommandDispatcher.move_to_start_of_document
qutebrowser.browser.commands.CommandDispatcher.move_to_end_of_document
qutebrowser.browser.commands.CommandDispatcher.toggle_selection
qutebrowser.browser.commands.CommandDispatcher.drop_selection
qutebrowser.browser.commands.CommandDispatcher.debug_webaction
qutebrowser.browser.commands.CommandDispatcher.jseval
qutebrowser.browser.commands.CommandDispatcher.fake_key
qutebrowser.browser.commands.CommandDispatcher.debug_clear_ssl_errors
qutebrowser.browser.commands.CommandDispatcher.edit_url
qutebrowser.browser.commands.CommandDispatcher.set_mark
qutebrowser.browser.commands.CommandDispatcher.jump_mark
qutebrowser.browser.commands.CommandDispatcher.fullscreen
qutebrowser.misc.crashsignal.CrashHandler.report
qutebrowser.mainwindow.mainwindow.MainWindow.close
qutebrowser.browser.hints.HintManager.start
qutebrowser.browser.hints.HintManager.follow_hint
qutebrowser.browser.greasemonkey.GreasemonkeyManager.load_scripts
qutebrowser.keyinput.macros.MacroRecorder.record_macro_command
qutebrowser.keyinput.macros.MacroRecorder.run_macro_command
qutebrowser.misc.readline.ReadlineBridge.rl_backward_char
qutebrowser.misc.readline.ReadlineBridge.rl_forward_char
qutebrowser.misc.readline.ReadlineBridge.rl_backward_word
qutebrowser.misc.readline.ReadlineBridge.rl_forward_word
qutebrowser.misc.readline.ReadlineBridge.rl_beginning_of_line
qutebrowser.misc.readline.ReadlineBridge.rl_end_of_line
qutebrowser.misc.readline.ReadlineBridge.rl_unix_line_discard
qutebrowser.misc.readline.ReadlineBridge.rl_kill_line
qutebrowser.misc.readline.ReadlineBridge.rl_unix_word_rubout
qutebrowser.misc.readline.ReadlineBridge.rl_unix_filename_rubout
qutebrowser.misc.readline.ReadlineBridge.rl_backward_kill_word
qutebrowser.misc.readline.ReadlineBridge.rl_kill_word
qutebrowser.misc.readline.ReadlineBridge.rl_yank
qutebrowser.misc.readline.ReadlineBridge.rl_delete_char
qutebrowser.misc.readline.ReadlineBridge.rl_backward_delete_char
qutebrowser.misc.savemanager.SaveManager.save_command
qutebrowser.misc.sessions.SessionManager.session_load
qutebrowser.misc.sessions.SessionManager.session_save
qutebrowser.misc.sessions.SessionManager.session_delete
qutebrowser.mainwindow.statusbar.command.Command.set_cmd_text_command
qutebrowser.mainwindow.statusbar.command.Command.command_history_prev
qutebrowser.mainwindow.statusbar.command.Command.command_history_next
qutebrowser.mainwindow.statusbar.command.Command.command_accept
qutebrowser.mainwindow.statusbar.command.Command.edit_command
qutebrowser.misc.utilcmds.later
qutebrowser.misc.utilcmds.repeat
qutebrowser.misc.utilcmds.run_with_count
qutebrowser.misc.utilcmds.message_error
qutebrowser.misc.utilcmds.message_info
qutebrowser.misc.utilcmds.message_warning
qutebrowser.misc.utilcmds.clear_messages
qutebrowser.misc.utilcmds.debug_crash
qutebrowser.misc.utilcmds.debug_all_objects
qutebrowser.misc.utilcmds.debug_cache_stats
qutebrowser.misc.utilcmds.debug_console
qutebrowser.misc.utilcmds.debug_trace
qutebrowser.misc.utilcmds.debug_pyeval
qutebrowser.misc.utilcmds.debug_set_fake_clipboard
qutebrowser.misc.utilcmds.repeat_command
qutebrowser.misc.utilcmds.log_capacity
qutebrowser.misc.utilcmds.debug_log_level
qutebrowser.misc.utilcmds.debug_log_filter
qutebrowser.misc.utilcmds.window_only
qutebrowser.misc.utilcmds.nop
qutebrowser.misc.utilcmds.version
qutebrowser.app.Quitter.restart_cmd
qutebrowser.app.Quitter.quit
qutebrowser.browser.webkit.rfc6266.Charset.grammar
qutebrowser.browser.webkit.rfc6266.ContentDispositionValue.grammar
qutebrowser.browser.webkit.rfc6266.DispositionParm.grammar
qutebrowser.browser.webkit.rfc6266.DispositionParmList.grammar
qutebrowser.browser.webkit.rfc6266.DispositionType.grammar
qutebrowser.browser.webkit.rfc6266.ExtDispositionParm.grammar
qutebrowser.browser.webkit.rfc6266.ExtToken.regex
qutebrowser.browser.webkit.rfc6266.ExtValue.grammar
qutebrowser.browser.webkit.rfc6266.Language.grammar
qutebrowser.browser.webkit.rfc6266.NoExtToken.regex
qutebrowser.browser.webkit.rfc6266.QuotedString.grammar
qutebrowser.browser.webkit.rfc6266.Token.grammar
qutebrowser.browser.webkit.rfc6266.Value.grammar
qutebrowser.browser.webkit.rfc6266.ValueChars.grammar
qutebrowser.mainwindow.statusbar.bar.StatusBar.color_flags
qutebrowser.mainwindow.statusbar.url.UrlText.urltype
qutebrowser.utils.debug.log_events
qutebrowser.utils.debug.log_signals
qutebrowser.utils.debug.qflags_key
qutebrowser.utils.qtutils.QtOSError.qt_errno
scripts.utils.bg_colors
PyQt5.QtWebKit.QWebPage.ErrorPageExtensionReturn().baseUrl
PyQt5.QtWebKit.QWebPage.ErrorPageExtensionReturn().content
PyQt5.QtWebKit.QWebPage.ErrorPageExtensionReturn().encoding
PyQt5.QtWebKit.QWebPage.ErrorPageExtensionReturn().fileNames
PyQt5.QtWidgets.QStyleOptionViewItem.backgroundColor
qutebrowser.browser.qutescheme.qute_bookmarks
qutebrowser.browser.qutescheme.qute_tabs
qutebrowser.browser.qutescheme.qute_history
qutebrowser.browser.qutescheme.qute_javascript
qutebrowser.browser.qutescheme.qute_pyeval
qutebrowser.browser.qutescheme.qute_spawn_output
qutebrowser.browser.qutescheme.qute_verizon
qutebrowser.browser.qutescheme.qute_version
qutebrowser.browser.qutescheme.qute_plainlog
qutebrowser.browser.qutescheme.qute_log
qutebrowser.browser.qutescheme.qute_gpl
qutebrowser.browser.qutescheme.qute_help
qutebrowser.browser.qutescheme.qute_backend_warning
qutebrowser.browser.qutescheme.qute_settings
qutebrowser.browser.qutescheme.qute_bindings
qutebrowser.browser.qutescheme.qute_back
qutebrowser.browser.qutescheme.qute_configdiff
qutebrowser.browser.qutescheme.qute_pastebin_version
qutebrowser.browser.qutescheme.qute_pdfjs
qutebrowser.completion.models.listcategory.ListCategory().lessThan
qutebrowser.utils.jinja.Loader.get_source
qutebrowser.utils.log.QtWarningFilter.filter
qutebrowser.browser.pdfjs.is_available
qutebrowser.misc.guiprocess.spawn_output
QEvent.posted
log_stack
propagate
PyQt5.QtNetwork.QNetworkReply.netrc_used
qutebrowser.browser.downloads.last_used_directory
PaintContext.clip
logging.LogRecord.log_color
scripts.utils.use_color
qutebrowser.misc.utilcmds.pyeval_output
qutebrowser.misc.utilcmds.log_clipboard
qutebrowser.misc.utilcmds.fake_clipboard
qutebrowser.utils.qtutils.PyQIODevice.fileno
qutebrowser.utils.qtutils.PyQIODevice.truncate
qutebrowser.utils.qtutils.PyQIODevice.closed
qutebrowser.utils.qtutils.PyQIODevice.readable
scripts.dev.pylint_checkers.config.msgs
scripts.dev.pylint_checkers.config.priority
scripts.dev.pylint_checkers.config.visit_attribute
scripts.dev.pylint_checkers.modeline.visit_call
scripts.dev.pylint_checkers.modeline.process_module
qutebrowser.config.configtypes.BaseType
qutebrowser.config.configtypes.Bool
qutebrowser.config.configtypes.BoolAsk
qutebrowser.config.configtypes.ColorSystem
qutebrowser.config.configtypes.Command
qutebrowser.config.configtypes.ConfirmQuit
qutebrowser.config.configtypes.Dict
qutebrowser.config.configtypes.Directory
qutebrowser.config.configtypes.Encoding
qutebrowser.config.configtypes.File
qutebrowser.config.configtypes.FlagList
qutebrowser.config.configtypes.Float
qutebrowser.config.configtypes.Font
qutebrowser.config.configtypes.FontFamily
qutebrowser.config.configtypes.FormatString
qutebrowser.config.configtypes.FuzzyUrl
qutebrowser.config.configtypes.Int
qutebrowser.config.configtypes.Key
qutebrowser.config.configtypes.List
qutebrowser.config.configtypes.ListOrValue
qutebrowser.config.configtypes.MappingType
qutebrowser.config.configtypes.NewTabPosition
qutebrowser.config.configtypes.Padding
qutebrowser.config.configtypes.PaddingValues
qutebrowser.config.configtypes.Perc
qutebrowser.config.configtypes.PercOrInt
qutebrowser.config.configtypes.Position
qutebrowser.config.configtypes.Proxy
qutebrowser.config.configtypes.QColor
qutebrowser.config.configtypes.QFont
qutebrowser.config.configtypes.QTabBar
qutebrowser.config.configtypes.QTabWidget
qutebrowser.config.configtypes.QUrl
qutebrowser.config.configtypes.QssColor
qutebrowser.config.configtypes.Qt
qutebrowser.config.configtypes.QtColor
qutebrowser.config.configtypes.QtFont
qutebrowser.config.configtypes.Regex
qutebrowser.config.configtypes.SearchEngineUrl
qutebrowser.config.configtypes.SelectOnRemove
qutebrowser.config.configtypes.SessionName
qutebrowser.config.configtypes.ShellCommand
qutebrowser.config.configtypes.String
qutebrowser.config.configtypes.TextAlignment
qutebrowser.config.configtypes.TimestampTemplate
qutebrowser.config.configtypes.UniqueCharString
qutebrowser.config.configtypes.Url
qutebrowser.config.configtypes.ValidValues
qutebrowser.config.configtypes.VerticalPosition
qutebrowser.config.configtypes._Numeric
qutebrowser.config.configexc.ConfigErrorDesc.traceback
qutebrowser.config.configfiles.ConfigAPI.load_autoconfig
types.ModuleType.c
qutebrowser.config.configfiles.ConfigAPI.configdir
qutebrowser.config.configfiles.ConfigAPI.datadir
include_aliases
scripts.dev.src2asciidoc.UsageFormatter._get_default_metavar_for_optional
scripts.dev.src2asciidoc.UsageFormatter._get_default_metavar_for_positional
scripts.dev.src2asciidoc.UsageFormatter._metavar_formatter
qutebrowser.browser.webkit.network.networkmanager.ProxyId.hostname
qutebrowser.command.command.ArgInfo._validate_exclusive
scripts.get_coredumpctl_traces.Line.uid
scripts.get_coredumpctl_traces.Line.gid
scripts.importer.import_moz_places.places.row_factory
```
