sa-watchman
===========

[![Build Status](https://travis-ci.org/softasap/sa-watchman.svg?branch=master)](https://travis-ci.org/softasap/sa-watchman)

Facebook's watchman

Example of usage (all parameters are optional)

Simple

```yaml
  roles:
    - {
        role: "sa-watchman"
      }
```

Advanced:


```yaml
  roles:
    - {
        role: "sa-watchman",
        watchman_version: 4.5.0,
      }
```

Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa-watchman` role using the command


`
   ansible-galaxy install softasap.sa-watchman
`

the role will be available in the folder `library/softasap.sa-watchman`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-watchman"
       }

```



Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html

