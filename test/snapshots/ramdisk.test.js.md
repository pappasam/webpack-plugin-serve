# Snapshot report for `test/ramdisk.test.js`

The actual snapshot is saved in `ramdisk.test.js.snap`.

Generated by [AVA](https://ava.li).

## ramdisk

> Snapshot 1

    Error {
      all: `/Users/powella/code/webpack/webpack-plugin-serve/test/fixtures/ramdisk␊
      /Users/powella/code/webpack/webpack-plugin-serve/test/fixtures␊
      RamdiskPathError: Cannot remove /Users/powella/code/webpack/webpack-plugin-serve/test/fixtures/ramdisk. The ramdisk option creates a symlink from `output.path`, to the ramdisk build output path, and must remove any existing `output.path` to do so. Please set the `context` to a another path, choose a different `output.path`.␊
          at WebpackPluginServe.init (/Users/powella/code/webpack/webpack-plugin-serve/lib/plugins/ramdisk.js:59:13)␊
          at WebpackPluginServe.hook (/Users/powella/code/webpack/webpack-plugin-serve/lib/index.js:177:25)␊
          at WebpackPluginServe.apply (/Users/powella/code/webpack/webpack-plugin-serve/lib/index.js:128:10)␊
          at webpack (/Users/powella/code/webpack/webpack-plugin-serve/node_modules/webpack/lib/webpack.js:49:13)␊
          at run (/Users/powella/code/webpack/webpack-plugin-serve/node_modules/webpack-nano/lib/compiler.js:16:20)␊
          at doeet (/Users/powella/code/webpack/webpack-plugin-serve/node_modules/webpack-nano/bin/wp.js:78:3)`,
      command: 'wp --config ramdisk/config-context-error.js',
      exitCode: 1,
      exitCodeName: 'EPERM',
      failed: true,
      isCanceled: false,
      killed: false,
      signal: undefined,
      stderr: `RamdiskPathError: Cannot remove /Users/powella/code/webpack/webpack-plugin-serve/test/fixtures/ramdisk. The ramdisk option creates a symlink from `output.path`, to the ramdisk build output path, and must remove any existing `output.path` to do so. Please set the `context` to a another path, choose a different `output.path`.␊
          at WebpackPluginServe.init (/Users/powella/code/webpack/webpack-plugin-serve/lib/plugins/ramdisk.js:59:13)␊
          at WebpackPluginServe.hook (/Users/powella/code/webpack/webpack-plugin-serve/lib/index.js:177:25)␊
          at WebpackPluginServe.apply (/Users/powella/code/webpack/webpack-plugin-serve/lib/index.js:128:10)␊
          at webpack (/Users/powella/code/webpack/webpack-plugin-serve/node_modules/webpack/lib/webpack.js:49:13)␊
          at run (/Users/powella/code/webpack/webpack-plugin-serve/node_modules/webpack-nano/lib/compiler.js:16:20)␊
          at doeet (/Users/powella/code/webpack/webpack-plugin-serve/node_modules/webpack-nano/bin/wp.js:78:3)`,
      stdout: `/Users/powella/code/webpack/webpack-plugin-serve/test/fixtures/ramdisk␊
      /Users/powella/code/webpack/webpack-plugin-serve/test/fixtures`,
      timedOut: false,
      message: 'Command failed with exit code 1 (EPERM): wp --config ramdisk/config-context-error.js',
    }
