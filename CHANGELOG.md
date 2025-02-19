# @u-wave/react-vimeo change log

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/).

## 0.9.5
 * Add props for the player option. (@iuriandreazza in #132)

   Added props that matches with the latest version from vimeo player attributes, they are:
   - `texttrack`,
   - `transparent`,
   - `quality`,
   - `pip`,
   - `playsinline`,
   - `maxheight`,
   - `maxwidth`
   
 * Add the `dnt` prop to the typescript definitions. (@k-p-jones in #140)

## 0.9.4
 * Add prop for the `speed` player option. (@warrenmcquinn in #128)

   This option enables speed controls so the user can select speeds in the Vimeo frame UI,
   it does not itself control the playback rate.

## 0.9.3
 * Add prop for the `dnt` player option. (@k-p-jones in #125)

## 0.9.2
 * Add prop for the `onPlaybackRateChange` event. (@houmark in #120)

## 0.9.1
 * Add React 17 to allowed peerDependency range. (#114)

## 0.9.0
 * Add typescript typings. (#103)

## 0.8.3
 * Set `sideEffects: false` in package.json.
 * Add `style` pass-through property to set CSS properties on the container element. (@Authchirion in #100)

## 0.8.2
 * Call `onError()` prop if initial load fails (#96).
 * Call `setCurrentTime()` after a new video has loaded. (#95)

## 0.8.1
 * Add color string example to docs. (@ivoilic in #82)
 * Fix documentation for union prop types.

## 0.8.0
 * Add `controls` prop, set to `controls={false}` to disable UI on videos uploaded by pro accounts. (@ljmsouza in #81)

## 0.7.0
 * Add `responsive` prop that automatically fills the parent element. (@deJong in #80)

## 0.6.0
 * Add working `onReady` callback. You can use it to get access to the raw [@vimeo/player](https://github.com/vimeo/player.js) instance.

## 0.5.0
 * Clean up the `@vimeo/player` instance when unmounting.

## 0.4.0
 * Add `muted` and `background` props from new Vimeo player. (@pgib in #5)
