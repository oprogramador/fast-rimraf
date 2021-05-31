# fast-rimraf

[![MIT License](https://img.shields.io/badge/license-mit-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Build Status](https://travis-ci.com/oprogramador/fast-rimraf.svg?branch=master)](https://travis-ci.com/oprogramador/fast-rimraf
)

[![NPM status](https://nodei.co/npm/fast-rimraf.png?downloads=true&stars=true)](https://npmjs.org/package/fast-rimraf
)

`fast-rimraf` first moves the directory, you want to delete, into another location so in the blink of an eye you have an empty space in the parent directory. Then it deletes the moved directory in background in order to free space in your disk.

## usage
`npx fast-rimraf node_modules`
