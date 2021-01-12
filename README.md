# Komunikasi-Wireless-Arduino-XBEE
XBee Xbee merupakan salah satu merek dagang yang mendukung beberapa Protokol komunikasi seperti Zigbee dan 802.15.4. Xbee merupakan salah satu Produk dari Digi International. Xbee memiliki dua versi yaitu seri 1 dan seri 2. Seri 1 hanya mendukung Protokol IEEE 802.15.4 dan komunikasi point to point dan point to multipoint. Seri 2 melengkapi seri 1 mendukung Protokol yang ditentukan Zigbee Alliance dan komunikasi mesh. Perbedaan dari Xbee dan Xbee Pro bisa dilihat dari Tabel di bawah. Xbee mempunyai 4 tipe antena yang digunakan pada yaitu Wire , U.Fl, RPSMA dan Chip. Xbee mempunyai 7 masukan maupun keluaran yang dapat diatur sebagai I/O digital maupun analog. Untuk masukan analog hanya 4 pin yang bisa digunakan. Untuk tegangan masukan tegangan masukan maksimal 1,2 V. Untuk itu diperlukan pembagi tegangan jika masukan dari alat memiliki lebih dari 1,2 V. Di dalam mengatur konfigurasi Xbee digunakan aplikasi X-CTU maupun melalui hyperterminal, dimana dapat dilakukan melalui perintah AT command maupun secara visual yang sudah ada pada menu X-CTU.
data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAf8AAACyCAYAAABMQMa4AAAgAElEQVR4Ae29zYscybInGn/FgdhO7obaaadVrHJTG20EgxaxyMUrGC0aBBNDLgQaKKgLAQnNExxakFCIaRCnCBA0zTTFTTRcNIicm9M0NKLI95qZRhR5aEQfURQXIURhg7m7eVh4eHh+Z2VmmaCU8eHhHz//hZu7uYVZBPJPEBAEBAFBQBAQBO4UAtGdaq00VhAQBAQBQUAQEARAhL+QQBAQBAQBQUAQuGMIiPC/Yx0uzRUEBAFBQBAQBET430UOfB1B3oogity/NmT9AYyvb+4iKgu0+SMMsnsMxwTy0TUAfIAibZXXWzmMvi6Q/coeuYLxeQ/S2PR30oVifLWy3Fea0dUAMqon8pOwmxSQMr628hFsAtKvoxxarFz7ziQZnI4msLY35WYCw14KcXQAaf4TXIxOoVt8MFDvUH+ulByS2SoREOG/SjR3Ki8juGhwtYNNBHGngMu1jWo7BdIMlf0Eo/wQough9MefTfovcFk8hjhOIT8fA04Hbu/fDVyPvoW0ew6TG4CbyTl0kxii+DEUl19ur1qhkq+HkGMd230YEw9vfoeicwBx2oPzDU9cbsZ9aEcxtPsXWthf/wr99GB9GGL+WQ6DCfbPF5iMCsjT+5Aq4b+D/Rnqa7l3awiI8L816G+74GsY5Um5ssLqmAE2ig7h8YN/V65c2cpHrbi8moMDSHtvlYAB7/0YkuwljNSA9hUmxZE3f73SM3Vj5eoVV0gz8RnG/YfV9rgQ31xAvx1DddXIyqoIRL56pxW9m6E5V6tVEg43cH1xCp3OKVygBsWUaVeMUQRx+hyGCgcAcFa0Np0SfE04UVm8PlcwLrqQIGZxCr1353B6+jN8hY8w6L0qhSjcwNWgC3HUMsKkzMO/ysV+68PAJ3DXhaetI02oruCi/w10+r/CNZh+5tzA9g5pFT4FsyDeJRb8SOPCOUBlJJD/z/+lOGX7TfWv6XueCcy4WlcTCxL0ZQY345dm5T97f5ZPy5EgUEdAhH8dkztyxSP8gQQhDnQXUKT3KgLi5rKAxz1St6JwpPtfYDJ4Bkl0AJ3id6MK5fcB4PoCiqzNVnNmAE0LmBDiOPl4/NyoyN375eDp1UygIOqkkCaP2AqcMta/N+NT6KSPIOErSkpCQiHpwchueyAeT6GYTFEwk4Bvv4DReyb4K3kf6XxuLmHQbUOcDUAr3o0w5nW6HsK3fRTc+A81NPfLVSfgyu8U+mp7gQoAUKvTuAP9C8xV98dhk2pctbUu/FVu6p6pK5Y1/gnyhlXu2vDEeahdbb+D91bwU3s5twz34i4MrkhNEMJsGt5UBv2ayUYtf9zu0ZMTXVczUVHC+x7rL2yM6XM76cPJTAfiCtdMebTtkTwzK3+qR+A31J+Bx+TW3UZAhP+d7X+f8Kc9bBzI/n8m3H0g8QEYgFb75araua+S5NCibQZwhbtbhu8+rVrvQTb4WHkABdFR/w2cVwQlT4KD+FPoD3+ALKYVJbs/KeAoO4HjpAVJPjSq+hmFP1+NegZ0JRxsu00b7KRHC5cSN1YnPFQTi7axJXDu2VOTJxdQNxfwUq38bSJ7UBFW9qo5qAh/c80IpHLCgtfXiSe1O4Yoill/mPq4mKj60YSFnm3CbArepgj7YyZ2tu03ExidZpCweik87eRNv1dlf+otoFbqaAOUdoxrE6hEMzFQmo2QpovS00TJw+kyiRwJAjUERPjXILkrF4zwt6vFUm2sV9aO8MZVee/HcpWujNrMyt8OiIeQjz4ZAJ3nzcq/XLW7wh0HyRfw2q6y3fsmW7OlUA6ueN0IovG/aZW2HYhZX+IgfnQK4xt3VWjSoPDPh/Bp1IMkonbMKvybJyVAKmwl7HElXUCWHEJ3cGk0JFifQz2ZwRXi02/ZChYAULC19KoW9+uf5m+MxoC1DQ/NPvn0PXHE6lFdoFJ2PuFPGiE7gTECdm14YmXMRJRPaKiOXNgrXh1CYmwaVJIgZlPwpjLMr54oHcCj9AHEtNWQZNAfkC2H5qmeHHyByfA5pDHxx/QfP6f8G4U/JsB9/peQod2D2cZpth2Z0p9UnvwKAg4CIvwdQO7OqRH+NKCpX21ZrK39UXgzi3W8b1eriBK/j899D68r1s/8Pn1VwFc6RrhXymertybNgE/4o2B/0NPbBUow1FdBOIg/UGpwI6jdCYIS/rilYQz41Ar+aga1v97jT5MEkjhy7AkQJxdnR2th2kN7xnaFaYhY3Yd3njVp6OdmMoRT3FrBVam1r6C7+he3bo7IHqF6S5/NKPzXhydWA1e/R5Ak9yGOOGd0FauYRGwLxXffwWwK3joH+l9rCSLfBISSuP3rmRhUDBfNc3pSwfluMywPcFJd5OYrDY8GBOdg0/qzzE2OBIEKAiL8K3DcpRMjlPhqrtJ8Z+XeuPL/Ha5HPWjXvhBwnqc9f2tU567s51n5Vw3e9EBKEwz8rd7XmoGHjoGhM0Gwwh/lNVpz34OkewbFSWjP3wj+Nu7PXurP/txJhZokJWabwrPXi8KWhMvkB8jt51zYGXxVicd/nW5/wFaNpZbFdCxqB9Lj8F5ySPjbthmhWJm4rQJPrKcW/G1cyX/Cz/7cvuSYGPwrK2t+34NZEO/KC2CNNd0JWSWV2ha4D9ngD4/WSb9jVS0VPq0nmMF8WSHlFxrcrsFoe6b1J8tHDgUBjoAIf47GnTqeU/jXsOHCHQezR8zYDxPz++ZhJVjI0EwP0lVtAi/Ed998QmfV8pgeBdERswHwrOxxgD58ytTpHtU/F/5mRdVR35s3rc644MdPskx9K5/8kdq3zKNqOe6pK4egZuxXuRk8qa0scfLWpc/HAo96hD+uLjsxW3muBU+sExP8ynYPOdRiRqKYBvsuKQ1Ra5ogT9/a5k7D2yZUBxpDd/JRTaO2ZciGhG036FQ+4Y8Gm3xryckP23PIjU7xPnGr5JH6MmeW/nSyl1NBgBAQ4U9I3LlfHCTvQbNKEwfeg6rVMq7eu7Qn7Qh3NfDx79qd+9aPAO2HmgHNriaxA9Du4ARyZcznCn+y9o+r+7tqNfsts9Cn/e8Hxv7AfBdtjfiwHDMAc+M8R/jjvqv6Vj9iAy5xhGwc+POYq7JQP4BUfZLGyjFtvJm8hR5aztvn9AqQrwyV6p4wVvv43HBN7wV3Pfv+X0c9eEDfoSsh2oGYsFW2BE/NlwCmET77ArxVEf7M2t9an68BT8RObVkcOrYIpHanrxiob80XHTVO0f0mzKbgTf2ruk5b6Ee+/rfpDI8IZzUxadf7n9vVKGdLnCM2M32gJjN824bsROLS/8Y8/elkL6eCACEgwp+QuEu/zr5nVNtXNSuuilpXq9WVqtJ5XgsvEpZc/e4cW6c3tJJx7mN5SgWOe+2Jo6bX36/nxUj7EsD+YvUoBajRaKi6t+Bh+tB4aGN7x+w5Nbj/66vSexy3a8DVcudJVdWuhGNZbyrX3YeO4v8MZ//1/3HawL+Zb8LYrLCdcsgmAH0wlEaVJWm/oge4rAPtxHgcJC9+tN1S68v6irbWBvUM2nMUxj8DQk4e71aEp13VEqaUL+9HfS/+j8/gP7jt4HvsQcx+qduwqLyYRoPgrOVDdaIE+Fvd+tA8YLy2PCoNabEP4zSHomIbw/NETv8Mpy9/gUvl2OfA8IfZ4szRn07OcioIVBAQ4V+BQ04EAUFAEBAEBIH9R0CE//73sbRQEBAEBAFBQBCoICDCvwKHnAgCgoAgIAgIAvuPQE34l3uLtAcnv4KJcEA4IBwQDggHdpEDTdMYr/BvSizXBYFlEcCXR/4JAvuAgHB5H3pxv9sQ4mhtJA4l3m+YpHWbQED4tQmUpYxNICBc3gTKUsYyCIQ4KsJ/GWTl2bkRCJFx7szkAUHgFhEQLt8i+FL0TAiEOCrCfyYIJdGqEAiR0V+GcUZkv++mb64bvpMnV7n+zJa/ah3L6G+vL/D7euuSlxwRmb1R+tZ++VIlhy1EYO1cjpy4BCvGoPTZ4OzlJxmchnwRrKwe8r6sDMqGjEIcFeHfAJpcXg8CITI2l6g9s1H8dJ3OOBWyjoO005VZ/aU3lxW4gz7/M3KRi972CsjT+8bVrPF8Z6LLlf7YH0Nxie5/5d++IbA+LhtvkeueyFqvlMzhk4prcQCRjcGxrl6T92VdyPJ8QxwV4c+RkuO1IxAiY7BwFa2PBintV7/Do9PZACsfg9ksfFMNiiToy1xuxi/Nyv8jDHqvYKx80uN940c+olgG5TNytB8IrI3LxnvgWieypgv06p+0aXiRvBTya+voL3lf1oGqm2eIoyL8XbTkfK0IhMgYLFgJ9xii9gsYvT+FiuCnFcw6V0pq8hFBZH3cB2urbyo3sSL8Z0BqJ5Osi8uw7omsRZtiJ/BogbTN5kRptM+s8UDel5WDG+KoCP+Vwy0ZhhAIkTH0XMWXug2MQ08YlX96Ai9UPHvcw2xDd3AJ5UKcx0Z3hHglbrpzj4qgYDnK9qANWX8A42ubu03FD3Sgn1sYRHkl5HhtCKyHy6TyTyF/kUFC8QfMdpJuDG05ke9/xvWZuGwgMRNqq2GggFURxjt4C+PiSMcWwEn1p0sY9lKIbRyQKxgP+pAlsUmTQm84Kd83hroNaBUdQNo7g373rzD6yhJQdVRgLHlf6sgsfiXEURH+i+MqTy6AQIiM4exIje4xglKDWAuS7KUOQEP7lq1cDzJ0TgZ4aoVh1Jqhe7UK6ah6fMDLz8dwXUuHF3BC8siJUudNKBd3FIG1cJkCBlmjOwxz3KkIXX3ehqy4gGsVOrsFKrDQXFwuo1A+Sh9ATAa1PFCS2bpqZa/gvP8CzgfPoa20a3/CKD+EKCaBb2xyvJq36nugbGEwZHFN+FfT7Sgltq7aIY6K8N+67trvCoXI2NxyvcefJgkkcaQHOpZYrbArA4+JCKeEPw1MZHhHhoKo6qRBzHcvsKqvrK48UeFwG+KygCNuk8DqK4f7gcA6uOxT+Zf78ldwPepBEh1Ap/hdrbKRZ50YJ8T/nxHIs3JZa8uaQ3pjH+EWwH24n3SgN/pkOo0m4Ty6JF3zhL8G8y7ayYy/7+V98eOy7NUQR0X4L4uuPD8XAiEy+jMygr/9DAaTSxhk9yCy8dPxCT2IWdUlXuLqTGso+B6uxm/gLE8hpvjqoXv+ylSulhb9fM/UxJRPj2EwESv/CmB7drJ6LpPKn/OJC+k/Sv5fjWFwlkMaH0Da/xWu5+Uyf0ea+sXmeVGq881z1XeQJti83pTpDVyPi8r2QE1bdj2EXN4XAmylvyGOivBfKdSS2TQEQmSsP8sFPwpSskRm+4JqMHrAYtzjJ0S4OtIrk8q3zKjSLN7A+PoT/Db+A77Y2PS4z1+9V1v3fx1BjurKyj4/1YeteG5+h6JLnwPWWyRX9geBlXPZt1WEgjFp6e0j5GCLvslHu5MCBuNPcP3bb/BhmEOLq+4Zz2tcJgPZiL6e8fWJWc1XNGr4Cuo6qG0G85jWPvg1YGXOuGX2A/SVTQ7bupP3pYRoDUchjorwXwPgkmUzAiEyVp4i4yPHuE8b0ZnVDg1iVhNATkOc+2hohKsjTD8Zwml2qAbTK2Vg5L9X28dXg15c2hVAuaKJOwVc4gh7cwmDp0+hf3FVNkVd+xYGV74huEwmR7uHwKq5rDVWj6A//oxkguvxT5CnBxCnp3CBk05ardvzCYxOM0iSHgxH30G7gec1LiMnu22IIjZprcGvVf7tPlv1Yxqqg+I8eweoTrV8rmHUy6wxYLlN8VHelxpWq78Q4qgI/9XjLTkGEAiR0T6mDPJohVPu8VdW8bjKwVXJ5QUM+mQVHUGc5lBUvJNdwbjoGqtpff9sQEZ6oXu2Nvrg689w+vIXuFSOfcjKWnv5U1b/1xdQ2C8NyrpHwdWVU4ac7hQCK+fy1T9qFvR5MYKJnTeWwhbLRoO7/Aw1WZhgRi4771Zkrfcd6NVk1/etv6cOlTo6+eCe/7fPoXj7HNIY3wu0+H8Lkyt5X1yk1nEe4qgI/3UgLnk2IhAiY+NDckMQ2EIEhMtb2ClSpQoCIY6K8K9AJSfrRiBExnWXLfkLAqtEQLi8SjQlr3UgEOKoCP91IC55NiIQImPjQ3JDENhCBITLW9gpUqUKAiGOivCvQCUn60YgRMZ1ly35CwKrREC4vEo0Ja91IBDiqFf44wPyJxgIB4QDwgHhgHBgtznQNKnwCv+mxHJdEFgWARxI5J8gsA8ICJf3oRf3uw0hjtZG4lDi/YZJWrcJBIRfm0BZytgEAsLlTaAsZSyDQIijIvyXQVaenRuBEBnnzkweEARuEQHh8i2CL0XPhECIo0sI/w9QpK0G2wD0hPYCCutMZaZ6SqI7gECIjP7mo1vQH7VP/rSAiT9R+Or1GM7Rp7+yZUFuFlPD8YYzpLvuO5BA/m7AXLDiXmEL0uKDeqDqpCjkXY3yl99tRmB+LlMkvXIPuRKTouKoh6L2LYhAJfgUOetxHPRES5bBq+Y6D2rl8O4dczms3j3ivAn2Q7Zli77XvHw59iIQ4ugSwh/LomhORC68xsOexpBU4lB76ycX7xACITJ6YeCDykKDBAYdeQzdwSXcIDcHz5S3P+uS11voHBfRN3kHPf45/srdayZLHYGQIq/NUY4k3ToE5uayipJ3ZNz3us2haJOaGzpo1D0bvc9NHTq3AacwXsXr0kPgzeVr6HbNxNe6+GVxMkKZznBPu+41njeNO2vfNZ2VCchFrrFnyF+SzI9AiKNLCn+M84CzOy78TQVVQIq4OijOX3d5Ys8QCJGxualmhb2I8L96A71T7p8cfZbfm+LXvLkmvjs63gAT/jgtVnED3MApOFl+Coeuv3RfpnJt6xGYl8vIicNsACzyQ9lGE8Cn9KXPo/lZ/75l+qYjM+7aeABN6fC6mlivTvhThM1qmGDTjsgtB9/DpolQqNJybx4EQhxdn/C3WoHICcE6T9Ul7b4hECJjc1uXEP61TD2R+Gpp5rxAwU74wG6uVUOfyoA3J7JbnXw+LtOkE1X+ZltURd7Tgt23iPJdCwNCoXVn0SxprW1rxSvvmSfCGC74sA/jOeY14bbLXR8CIY6uUfhjrIkBZBjMQYWF/AyTIQV3MC+A2hJw9n9aOYy+0qwU0yVwUvwIvZSCqWD4VYztLrHSfZ297ddCZGyu+yqFv1mJ2EiATqnXFCf9CM5GbwzvzPYVD0YSd1j0Ps8qjbjPVzwy4Dlg7/bpQlxGfhWFtmGxQZ9oQuqsjtXKvLQZmYoWcS55DBmNl3FqI+qVz1+ZAEIUQbC8Y48Weg9Y1D87EaatYb4IFA2YxXnNByGOrlf42/jTR1Bc/gr9dgzawIUIQdsFV3DR70Ac8xkrzmK/gXz0dxj3H5oJxI2dUPB40mvGT7JfIQIhMjYXs0Lhr1bkDyAfffIURypKPjk1e7ERRgR8DsPJF6B9TG6sVV3x6MGtnT6CxA7wMuB5AN/pS4tx2TSZNENqK4uEPxnEmTRzCn+tKTjQUfMwAvDkHLpJDFFlXHUWW5V71B2Lvwd11T9qPB5CmiYQ2YmwaMAI6XX/hji6XuFPM1G18jf6HTuj1Kv6fGSiTdNeFc0Ya6sknK2+UvGtsUEi/NdNm/XkHyJjc4mrEv4oyDPo9H+FWoxzWzgNfGwgrg3CnvpUVP9mcLv4WU14tepfBjwL8Z4cLMZlarzhmdJArVL404IKy6FFlkd7wMZh/1i64Htg7V2MDYwZxy8u+tCmiXBtbCdM5HfVCIQ4ukbhT8SLzGr/i1H7tyHr/wDvimeOoSCtsFD19QnG/SPIBh8VFjeTt9BL76nPB1+/K+CkJcJ/1STZVH4hMjbXwSNsa4lNGvp8iH1ip5PewPXoW0infn3iGYhnEf7Kkvue1lB9ODf7mSjw0bjwIfSHP8geZ63PdvvCYlwu26xW6mb7ybe/77umnyaO4gLK/KUFfPAZX9e4W5YPFe0Du64OqYw5J8H4rFn0xdk5fCADV3Mtar+A4bkYvbpor+s8xNH1CX9r7X+oVKxaLXpgP13xEptW/09O4OTwKQzwcxFaUZFhitlK8M9W1wWh5LsqBEJkbC5jFuHf/DTeUZ85PT2HyVQDo0UHPZrsHsCj9KGx6KdrMdxPErHyD3fRzt1djMvUTFxZPwJr3a+EI/86xKy8udaUHm36reVBX51Uv0QpH8fJ6f2yDuUNAFj0PcBMzKQ3fgDpo475tJEmwvcgSdKGzx0rFZCTFSAQ4uiSwp8GN65q4t/5H0BqVKxa+MeQ5EO4vpnAsIdOV1xS0uqfvQQ0O016MLoujQb5fusKMJIsNoRAiIzNVTDCv8lIr/lBdQf3Pp9mL+HiupT86lr+xvPZFak7S+Mr4q4dqImTbn1odWP3NstVULnfOaWycntnEJiLy6hmt9/cGy1oG8c04qQZ+5Qx82e4HheQJfN+50/W/sYY1XzL7/dpYXxeNBpPL/Ee2O0G18ivqx1tue/NzvT47lU0xNElhL+rZmUqqOgA0vx7eD2aAFEbrFMJbTj1bvg9dOLSiMrCqgbQcuBVToOMY5YILVffvYUzdKDitWK1ucjBliIQIqO3ykptybnF1JDeB/hF16MZz4dzjJ5xjKGiBI7zDFqkWkVbk+McjlssH/o6RWVhVjeVwc1cq6Sj8uR3lxGYh8vW+E5xCbc+B3Uvk3ZRhPxa0PteJQ/uzZIWasRdHKMLGHm/mlr2PaBJL1vEYUebybFobTfH+hBHlxD+a2rA1QC6RwVc2lnDmsqRbG8FgRAZb6VCUqggsCACwuUFgZPHNoZAiKNbJvxRbZVaQ7+NISQFbQyBEBk3VgkpSBBYAQLC5RWAKFmsFYEQR7dC+Os9VXQGlEJ+Pg58hrVWnCTzDSAQIuMGipciBIGVISBcXhmUktGaEAhxdCuE/5raLdluIQIhMm5hdaVKgkAjAsLlRmjkxpYgEOKoV/jjA/InGAgHhAPCAeGAcGC3OdA0D/EK/6bEcl0QWBYBHEjknyCwDwgIl/ehF/e7DSGO1kbiUOL9hklatwkEhF+bQFnK2AQCwuVNoCxlLINAiKMi/JdBVp6dG4EQGefOTB4QBG4RAeHyLYIvRc+EQIijSwp/cgHJ90TmccIyU/1ZIgpFeQBp8YFd38NDGxHRE5Rjh5sbImO4WeibvwdJ5PLrCsZFFxJynlJcyNciYSDl7ooQWJjLNxMYFTmkGO484t5R5+fyzWQIp1nb2Gi1ITsdOi6s589zRfBINluAQIijSwp/0zpya6rCU66vxToeAL4wuyEQdX2XqGvN2+H6sN1UziEyhupQekjjwt+4RDVhSXWaeV2ihkqVe4JAMwKLcNnyOMmgb939YhkLcPnmdyg69yBRwapu4PriFNK4dKm+UJ7NzZU7O4hAiKOrEf4bDLaztEDdoQ5Uba24it2hyjdUNUTGhkcA1CD3wMQEZ8JfBYJqscAkCwRDaSxUbggCYQTm5jIFLktPK3EmVClzc5nc9XI31Q7/584z3F65u3sIhDgqwn9r+xNfZBb1a2vrOV/FQmT054Qrom+gnb+FcXEEEVP764kgV5sC+K7585WrgsByCMzHZQq68xiKyy+1gn289V0rH6QtVzYZxlh8LKwvP6bnfNfonvzuHwIhjq5H+FeCS6Cavg3dwSXcAAZaeQNneQpx+gIGbK9W39fg30zeQi89qPsasDGrSZXOgwuhEPgTJsPnZi8Ny42NSowFqlABVujFYXtuS9a5Qhu7Xx8BRh/8U72QWBbO0v/NROyKITLqanq23L+LITn5K+TtNuSja3MbsRtA3+7vHUDae1vu72HUsH5m9r55wKQSI6zLJ8L2lgLNhMhIOPDfm8sCOir62ReYVIQ/9SFf+QBAU/xyxOcM91mP4Gz0xvDL8OPqAgrCNTYR0Xgl5FgQ8CAwF5dpazR5DBmNbTY42ZxcVnWhZ6qRUUvh/sm8L/J+eLruzlwKcXQtwl+76yVSsqhmXy6g3461UCfiu+FRzbkOQ0lGXmV0KE1uFP6/w/X4J8g7j6E3NNED6dlsAFc2rCStDFk9vmLfk9pM31+qzj4qqbrct3EKVP5xBsW7U8i6BYw/DSFv0YvJ9uuUQKf9vy4MrjDCEeFAAp/ODcZWnfgchhili84VDlg5bPshZMUP0O/9AIMXD9Wk5MpX7zVfC5GxVjSq+48ys1KiwY5WOu65edor/Ck8KZ8QGoyjcqKkJhoYadLiVquRXBAELALzcFmPW/T+Ati9f7UA+DdnYmuK8HLZFg+Wr7SNYBcwOKaR8Kf3JZSnvB8lqvt1FOLoWoS/ho+t8tESm1aatCq2xoFmVU73a2EfzcrVpNcvUQzJkyeQthpWaXaVx1b24JTjqMiWqrOHL3oyQS+efrni9Alk3dcqYqG6T/v5Zm8uyYfGUl1PTFokhBQmMZT3KTwmToJGMMjuQZTw2OBmokMYq+fvQZI+Z/HDPZXewKUQGavFo3DO4Kj43YSFdoW9e26ebhwwaYCjPvFpCapcq9ZHzgSBKgKzc7mqjte50OID3+H/vZDwV+HOraYTw/ceQ5agRhEXDa6mzNRd3o9qJ+75WYij6xH+NANVFq0DKE6S2YU/mL0xI8z07NZd+ceQpI8gibhlK/biF6P2x3jZP8C74hm07Kc0U4T/UnV2GWQEDQl3tfLmAhrv036+SateWBPHWBm4tY3WgIQWaQmwrHLl/yR/Cu2oxEfVpLLyp0GGP+/Wd3PnITJWa2EEcYOraYwJ/pntb9KzpdqTtkvsnfoAWxsIRfgTWvI7HYHZuewT/tXJp4+35TVaxeNixvzRxJ5X01kklM+X74Lvms7CM5mW94Oju5PHIY6uQfiTMCPDFkfoTlv5o2ibnEMXZ7CK6AeVvW1NXpwt/wKj/BCi6FCpuLBn9Gr7ADpmtVglulOPysr/I4z7D9kevJN2hjpXmKFU/swKXb2UZT1B3X8E/fFnANACp1Q1X8FFvwOxNWxz6qIainZTVrAAACAASURBVJ/4HKjV/rvBCZvg4E1SZ1N5WgtQ5l+p6cZPQmQMV8YzOJnBrt2/MNoB4h5tl/AcPc/L4MYBkuM5EZiLyzWu0nhltu5q90Nc9lT05hIG3XZVAzhXnvJ+eFDd+Ushji4u/NXqFAXQMxhc/AhZTMKGVqr63Brv0cq2JkiNipruK8HY5MSHVrFmpUt1oO+8x321ClbqcVrJR2R70FAvNcFoQZLcsxOJuevsUERPQh7Ci8FbeDP+B1wNuhBbLYB56VvPoHj3DsbX/weKtAXaxgEF/1PIskcQt0+gGP4G10CDgJlMXRvjNGOYVp3wkEMPphFRA8B2rPoRphAZHRidU8/gRBMd5ODkszGkbPrOn/q/xEJjx7QminsxRKyvnErIqSBgEZiPy2Ttb7YqjbDW7z1maSbtM3HZVkFrO0cF5GhEqJ7lXxLMk6e8HxzVfTkOcXRx4Q+0QkU1VBsy5lmtXLnjqn0Aw7PHEKOK/p+eQfoXrrrqQ5EnpSoLV7uXv+sZLKm36DdO4Z9OUvgLnStHP/+iBCc2EP9aJ2fwE85+jRHXu+H30EEDrlQbwpX1wv2xAt7jqhm3JgZjuLLahgXqPFEWhIYvJKToSwN8qUjFj0noPn0B8QUmg2faSl8ZQV7CJ5wsMI0GkMBX7TyANC9ghIZ96h8JfI1BnOZQjIwBJGk3yJ7CPHGbPyEyhutFuLE9e3zATvLqPCzzM9oTy50EjvMMWvY8gtZxDsctxs0twqxshxxtEwJzc7nCVT0Gja/NVh82rHK/Oqb62q01mxFEcQp5MSq//OGJZ8pT3g8O2T4dhzi6hPBfE0TXv0I/+2vNME3t/XcKmKypWMl2MwiEyLiZGkgpgsBqEBAurwZHyWV9CIQ4umXC36ieki4UY/Yhmpq9duGp8hWwPqAk5/UjECLj+kuXEgSB1SEgXF4dlpLTehAIcXTLhD9qvkZQoBMgq5JF9dgLeM1U2euBSXLdBAIhMm6ifClDEFgVAsLlVSEp+awLgRBHt074rwsEyXc7EAiRcTtqKLUQBGZDQLg8G06S6vYQCHHUK/zxAfkTDIQDwgHhgHBAOLDbHGiaeniFf1NiuS4ILIsADiTyTxDYBwSEy/vQi/vdhhBHayNxKPF+wySt2wQCwq9NoCxlbAIB4fImUJYylkEgxFER/ssgK8/OjUCIjHNnJg8IAreIgHD5FsGXomdCIMTRJYU/OV7heyKOE5aZqjhroisYD/qQJU0eAGfNZ53ptLteBL38o8iCnnJvJjAqMNQspQ983WAddqCjn5/gYnQK3eKDJ9PtvRQio7/WX2Ay+tGEgXb9PGDwqJ+0dzOFt+sYBe8XOtgJhnfOCqg4VfEXKFcFgZkQWC2XfUWS1z0aG8hbqS/tnNcqjsOmvRtXMD7vlWOU+yl2pehdGKMrFd7rkxBHlxT+BjflQjaCyBdsYoXQWo9WyrvfNgs9xw1xAwbW4yB/ma7HcK4+dWQuevF55fwoh4Hy7IcCEV163od034W/8r9vBj+XXxjAKD3WmJBv86iM7aCDQpnzmjvVhk6Ry4LAjAiEBlZvFiEu+x7AcfWwD2PmBNCXbO5r6Ba9e2x8qZCHUebmupIhBhH7FtLuufIgaMcs41K9kpQ8iqqJOMZf2eYx2q35fp6HOLoa4W/89WOkNe7odh1wloF9tptYU+vpxCWoYmXiHZCLXxT8HkF/M355B1b+iIzRplSEP06wXsCpCo5k0KtMQo0vdeanX/vyX+HqqdppcnbHEAgNrM1Q+LjsS42r/iMT2dN3f5XXsE4HUAbI4nl/hEHvFZuA0MKmWbhPHft49nK8VgRCHBXhvybop70AWhBF0BRtTz9v7pNQqwXuWFPl15htiIzNxc46YLJ0vgmp71pzoXJHEAgisFYu0ztP21n9MygGYyiD8warNt9NLKtFUVhneLQWDbP6zLSxr5paztaJQIij6xH+dm+a9qooiA3uwb4x+7cvYFB0dUCbiO5rGGxUvcq+ud5W+KBiuNOs0wz2Kh3uq/8Jk+Hzcm8K93mVuooFrlABW7itgtmPX7LObgeGXwDay2tStVGsbwzageFp/2HC/CKebcj6g53duw6R0cWwPGdCvbxYP+KhlNUA5eIbyOd6DIMztL04grPRG+hhlDTiz5WJpIg8M9EU64XLlbuGwFq5rMDU42VRfG/sWsqIlKvBGvMfQD87bFj1+0vRC5fmulTHPneMvoTx4JXesjx7B8Oe8eaqFjYfYWxlgrPt6a+KXJ2CQIijaxH+VfWqUWGj0P1yAf12rA3hVAS7Cdy4YVTNuQ51iftNPUiichAvifW7NvbqPIbe0ESxo2ezAVwBqafI2I7VQ+1NVO8vVWdPB5T19G1P0GSEJjHeDCBXUebIgBL3+V8a4zUTyet8TSsBT3VWdSlExuYyAkKbPaT6MOnpoFDe1UlTPjQZw8kVTRhNOFQTIXI4+QLahqBZW8OqIod3AIF1ctmFT49PgfHCfWCGcz1G0QKttJUJP4rvyiNQYdMbEpZjX32M1u0wZRpNJr1XGJ1QjeV2SxQXPqs2eGio9J5eDnF0LcJf48hW+bhiohCpRvVaGgcaQUj3jbqrtB+oDtiaWDEkT55A2jKxsd2Os6s4JBkJf6cca5xC9zGTBevslm/zbnpZSdiUk5paFqT2I1woQeXrgDj4EtIj2/QbImNzPasc8KbDAePoG+hfmIBQcwl/zJH6hCZbpH3hfThDPbyVk4v7iMDauOwDi2u1fPcXvobW+bgSPyjH6EBeKKiPOqdwwUMRO+mnjdH1iYz7XpFmlr2LThlyOhsCIY6uR/iTCj3JoP96AMVJUhJrmvAHY6hlVnB6VlgKSUus9BEkkasa+mLU/qga/wHeFc+gNavwX6rO9Y4oZ7++lT8AzYCb9vyn3p+cQzeJzbbA7syOQ2Sso0hX3MGBrtMvcuYxdHnUR9/+vu8aZQGeAac2gZhWD5uZHNwBBNbD5SbgcPHSrqnnP336BPj35s2bxj+8H/7nmfj6HuBf1/jum2vhMXqWSbXnXQyUJ7eaEQhxdA3C3xDJfgrirLinCn+M7GcEm9rLP4C091Z9ZoJNLIXqLzDKDyEii3hct4/70Gafeum0tLJ36mHzwvsfYdx/CNESdXbhL+vpCn/96Uznux/gbx3cV/btnZkJELUNMTs06mxb0G6+ICEy2qbVDkJCF9Xzx55wz2abZ2Zrfw+eIvxrPSEXSgRWz+Uy79qRWvk/gj7/ugVACf7lhb/ZAmXvSr18/DyQPjWu3a1cKMe++hitEk59rzzvYqUEOZkVgRBHFxf+tC+D+zYXP0IWH0I+whkmzSL1uTXeU4ZrNyi99V62/WzLDNJ0X5G8yYkP7dMbTQDVwQhtLfyNKpxW8hF92tVQLzXBaEGS3LMTibnrXOsJp572Pm4roNMZ/RLbSU6SwSmFLLbf+TMjSIUZOuJ4CSP1nT/lE4O2jbAFbP1BiIzNlTfCvzY44TfKOWT9X5kVNF7rQT74aPboDY7GqUkzXsSPcjJGfLKfQBmbkqhWj+aay539RWC1XOY46e1HG8ZcjWUdaOdDxnOefrljPQ4dVjVnPEv0kfH0abmlhvfUtW89e/LO2OeM0epRtUgrtblQe6/q7yKvjhzPjkCIo4sLf7iqWqAXF5aYVqihWr43gOHZY4jx+J+eQfoXMjBB6/0+FHnCPOEdQXH5Owy6bXbNpI9T+KeTFP6ihDVew73Yf4Eibdm0rZMz+Mk8G6fP4d3we+jEEeCxMtiyGgXt0er94ARauDUxGMOVvbdAnSfcu4ERVLaerL10jQsPtE/oZ+arB0yLdevDYGz2rrGfv/4Mpy9/gUvl2Ae1BZhOe/nbNY91ITJ6Ka1WCRxD2ge8YpbB/H4EpXCmbSDCtcnDn9EKUf9ECRznGbTseQSt4xyOlQGmKcu1xfBWXi7uMwKr4zJpLSOI1HbnZ5gMnpVjghmjVvaZH9kTGX7HaQ4FLT6ww0gYo+Zx8D+gyDzjMTPC5n2sV/30PtbHaD120X3fe5VBfsxlAmlueSlyPCsCIY4uIfxnLX7OdMqT3V+1xTZ7VO39d1z3riyBHO4EAiEy7kQDpJKCgEFg9VzGFe/Tmmr/tgC/GZ/CUf8Cdsei6LaQ2t5yQxzdMuFv1D3c3S3iqtReXc++7vaCLjXzIxAio/8JuSoIbCcCq+TyzWQEr/s96HGj1dtqNn5R9LoPeW9gba1uqypS7nIIhDi6ZcIf5fwICuXbnlRDqAZ/AXb/azks5OlbRiBExluumhQvCMyFgHB5Lrgk8S0gEOLo1gn/W8BHitwgAiEybrAaUpQgsDQCwuWlIZQM1oxAiKNe4Y8PyJ9gIBwQDggHhAPCgd3mQNP8wiv8mxLLdUFgWQRwIJF/gsA+ICBc3ode3O82hDhaG4lDifcbJmndJhAQfm0CZSljEwgIlzeBspSxDAIhjorwXwZZeXZuBEJknDszeUAQuEUEhMu3CL4UPRMCIY6uRvhbb3ra8czF6BS6hevWdqa6zpZIebzjAVemPWacuFivgtPS7/j9ufHZXHtDZFy4Fvhp0ik5SuKeEN0cMTJiYcKjRlAGj3LT0Tl6WsOQp22dtuZwiO0FqjgWI/k0iqC7A7+r4TJy8kcT5tznx4Q7s2pDxpypgfUGijzUjstmd/qFAX36kCVt5Zl1Uhw12HnJ11a7TOUQR5cX/sopD/l8psH1PqTrFP673Bt3vO4hMi4GjQm9a8KDAvIxPYA4dSKPoTtS5f1RB33SbpKnlEiuqCM+UXBDQ+PnqUM4VV7Qdi/K4hQE5HYAgZVwmU8oa4sTw21yX668kN6DTvE73KgAaBTMCl1aa4+Aze6rqw0pPfExD3q1iKo8jDi5b6/mI2fbjUCIo8sJfzXQ1gX9zfjlelf+q8AbI1Rlr2Gyirwkj5kRCJFx5kx4QjVgMT/hNsATxXTAxCZQUtwQAprn5x6bCUCpJagHiFKPkEtUilHh5iPne4fA6rhsXIK7wh/HqKTFIvkZJ2jIsQ//DL1T7n3PTEojcn89HW49AWDCv8Z1nce0CKPTS5IUt4VAiKPLCX/yEU2rrttq4bzl0irQfdnmzUfSz41AiIxzZ4YP1CKEqXCNKniUFtgYRbGnwj/rFdOcpdQGRBH+cyK4t8lXx2W/8K8J50okUtfT//yR8Gr517iuu06E/+5SOMTR5YS/G9ynP4DanlNtX8pEpsOANmc5pLgaG7yCDGPT475V99zsm7KgLHEKvZ/60O2N4CvgXtUryFOtcSjVV7jvZWaxhsTY8FY+hE/jN+WeGkWZsr4MEsiHYxj2UojtNRZRz9ozYICgb+Gn/jH0Ru6Lh+qxH/Te8EkBbykvrPdwYnxj4/7xT3a/OYrakJ0OYXKjI3idoVfD9AUMiq4J6MHqMBXDNjzJHun6p9/BPzN8gON19q5sp5qwfWTBcQ4gtdHxGPYKE94vy70IITIulLNRm8bZAGwopMogRisihpEKOFWGia6Wi/2BkRcNH588gTTman+P8LccIbU/79PvYTR8rvLAPu8OPsCVzR855WxPVCsjZ1uMwOq47BP+JMzLKJMKCt9kV90wWgEeNKyGXdV+QI8Z4ZW/jXBK4cUXGk9qFZELG0IgxNElhT+2gO8LRRDFKeTnYxPhD9Wtj6xQoWh/ceclnH/3sIxO18OB2JCX4tsrNeoDEyZY72kd5iP4PMpNtDVm8KfSVsMA34xfQW/wsQwhjELMrvSrL5ue2ZKauLqnq+6pSFs3OoxltwO5K/xJA4JlUFwCs/ccUXtQhdc+MmExaY/uADp/+wG+a6Og0dipyQKpkNWL3IRhH85OKPpVOVEoJ0MaH5q1q/yNhkYFSYp5eb9D0TmAiFTWpnwtUClEJxskliBuiIwLZUuTOavSLycuauVvJgIU2VGFIlV7/wdm77RaqsaGJkLUTx7hryZFzOCP84v6T6UxfUP1tBMPs59rQ05X6yFn24/A6rhcHY90y0n4O2r8JuGvOEfjpQ87sh8wW1+k/aQFEz7CFk1qvLAcL8fahcYTX3Xk2kYQCHF0BcLftAEtrgtcyRvLU4w9zYWiJRIKnS4Mrq5gpML5luSuqKEUEf2W2zpdSUgAPXEojV0+w/j0RRlrmkjdIPx1C9hqDetqQrbqsmiVHugv09Zyb5jCdOJ+9Hv4x6DLNAul0FACtlY/trr8cwCZwrR8Rr2YDRhiDV189AvL8XIHm4aBxmpnsOwtFf4q7tNb6KUm1HHyBHJlfGcmcwZb3i9AvLR8oH41Ez++eqo9z/qGIjnzrw1oC4wmALYMD8ZNAzlVR363GoHQwDpfxd33EZ/28AUvezmDgj2DjtXceUpXnK/axlTGW1XkiG2X6TwqxqxGK7vweOKpllxaLwIhjq5O+Js20OoeBfz58Dto08q31kYziDIDlSoZuYoK1aM9ODcx7l3hhllrQhqL1Osh9PI3NTVw08pfRw1MIVafaw2gwBU1xWu/vmDxrPWnjLWtDaxATUjQi4qrxn+B9/2HLM68A0ZA+A/f9+fCUFcFtSNM2NcGDHewcQcaWj1ry/h3xTNo3brwpzqySZAVrBxPI8BJW+PrF3Dbb56vCWxfv3qEv3qcNFc0wLplUP3Lya5/IOdtkeNtRiA0sFbrTX3fxF2XK/rp6njYdA1tWr6F1G6XVkums7rApkUCm9R73xUcXC+gr7STZgti7vGEaiG/m0YgxNHlhD+S5bAHo2se8ZmIfgTFv76CNHLVq7jC/gXG11NW/oSSCi/5Qu/BGrW0T/iDUavG2Tl8GJxAF1X+9K8mXPnLZgZt8zkNgH9w1yE39bfklf1lpwy+wtQvHK5A/w7qO1pbBj10BePRb3Bdqx+rw4diLgwx5xo+c76sut5lv/kGIWrBvL8hMs6bVz09qen5Z0me1bwZzOr9aHjhWfmXaVnf0MpfVYSEP20RcI5hAvZeTMyDtX6pt0iubC8Cq+OyyxXT5tpqncYq1JzqMffm8jV0n5KdVAArxTWamOp0+r2m7U7fRNfkZ4W/mSjUeOvW38P1QNXk1voQCHF0eeHf4qr50lhKqeC/0l4yM3y7/hVO+2/hioSsXfnT3nKpru0dPYfh5IuyK7gsHkNcEf5VIgPQ87jv7kxISLjaQZ0G+RcwGqIlOM7ItcCwBi62rOdwpGwScAas21MKAtZpVIZV+5rvyk1daJ/d7j3DDVxfnEH/DbNLsCtZI7CwDv/432Y/fhYMdX30S13io4V5eW5n8hYPElx6Zk/pE9y6scZsbJBgzZ73METGefPi6ctQ0KX9g75fWvtrg0YzQahNxDA17cMfQKr6nCYTZsWm+sf0DWmGVCFXMD7v6S0vypcGzAaM8THCud3nn2zpWsv/24/A6rhM41EfxnwdRXxUY8pnY4hK3/mjf4lzeJq9hAu2+FLXuNaTYCSbEzJCtnv+yG2jJfRsXXJHQrStWuPtDFynasjvZhEIcXRJ4f8znL78BS6Z17QIDZryn0qrf6+l+p9mv5/UYEfwqjg2hnyGjK9ewbe9uuX8F2vwx0hLeNZmyuVsFkFQf2oAp0FeW7FfXp5DV1l346A/gOHZY4iNYdaHYR96xY92T7kU3lSo+TXCP06fwBOVF25V0OQF0+DEyGPt/0Xvs5X160OhbCFKbIrxezjHrwFUG2iyVcewmHw1q356tgUP04cM1whaxzkct+g+2jZkkB+T4SBex68fLoxDHN2Gd8PvoRO77XHaP+NpiIwzZlFNRpMuxbsC/M57aBvDtJuMMqs56TO+f495/vU5ZC3jGOhfv4eUeFT7xX7pwwC3pmydTHkejI/zrNovOX7JIv92CYGVcFmtotn7aBdDBgk7+cY05OGvXGTZccPy0fk6gAFa7t+j3VUH/vriCbTUVuc7+Ne/NXn4M+WaL7n0wqKs70zjiWsgzeokh+tFIMTR5YT/euu9W7mbAZ+r/XerAZupbYiMm6mBlCIIrAYB4fJqcJRc1odAiKMi/FeFu1GZebcEVlXGHuQTIuMeNE+acIcQEC7foc7e0aaGOCrCfxWd6qjuZPXfDGqIjM1PyR1BYPsQEC5vX59IjaoIhDgqwr+KlZytGYEQGddctGQvCKwUAeHySuGUzNaAQIijXuGPD8ifYCAcEA4IB4QDwoHd5kDTnMIr/JsSy3VBYFkEcCCRf4LAPiAgXN6HXtzvNoQ4WhuJQ4n3GyZp3SYQEH5tAmUpYxMICJc3gbKUsQwCIY6K8F8GWXl2bgRCZJw7M3lAELhFBITLtwi+FD0TAiGOLiH8jZvTBewDtDU8uYAs91M2ZiWPAWv66KqX+VmfCUpJtCwCITKG8yZPfW6f8RgQ5AQlnNNid8mDZLMTleZ80SnLGygU50q+R8rBysiEsKanXQcu09o0a3rP+1rxUujct94mqV7y6yIwP5cxAuqPZXjxSobGc2RtPGWeNXmckZCjKpsvcsNxLFZcmIirOlHF8Y8NM24zYH79DW+N51OWYkWHy7xfK6rCHmYT4uiSwr8D3cGljldfc3JzBRf9x9Ap/g+Lj05+zwllMwEgl5N0ea2/fJBzBclaC5bMAZQh6SJA2IBRlQkbhSl9DMXlF+XutJuU7k8XKafxGXKPGjE3yY2J2Q3y0FYT9CgIfoB+1oY4PbUuWpWv9m6hPWRaF6zNE4750jN3xdbtMK8ruq++B8mUIDHsiTt9GBpYvcDwT4KdydXN+Hvokhtx87Byo0vCllyLdwq4vAm5qGYlYxjx9BgG6CLdcqmM2aHdlVN/o7vxU0hjCmeN+aBAfgqHm3A/vej7xZorh3UEQhxdTvh/24cR+SStCX8AuHoDvVPtt9wO3uT7HKl1WUAn5kFY6pVfzxWaAOyR8McXPXsNk/UAtrJcQ2RsLEQNDA8gTdENMeszbHPSgtI3fj3wSWOec97QA/F9SO7HzdEZ3TzVgPvQxAlwb9I5TpKPoI1xFOgS/1UCo1n486TqeFr6mh92nsNHGHRPbNAYfkeO6wgsxGVvRMkbuP7tN0cDpLmsnYaR1ovxwPRjs1MxFNwv4HT8uay4cUSmo5v6VtrO+4NlHD7dCB8Wer/KlslRAwIhji4h/J3SfMK/koQIHIEKEHGFA/eaVmmVcn0neyb8aVbvrCZ8Lb/tayEy+uuGq/tvoJ2/hXGB/sdL4e+LNui75s93nqs4KD6Cdv9nuMDQzBFTxTZmY+rNV9EsboBa7U8u4Dw/htOLCyiOjj2DrB6gW2q111gQuzFLehr0623AyfhRd1CGwmY5y2Edgfm5jHmYID7T3lUl3O9DpqKTmvHKt01TuVavY/UKL5u2Xcv3CdOW788VXA26Jp4IBkvLoF+81rErqpmu4GyR92sFxd6BLEIc3aDwR6Q/wSg/VFGkkuQ+qKhxgQ6wYXRbz6B4+1xHTTMBdyYU/cobOEhHApwM6Rncr9JBfPRzjvDn6riGl6m6N2aCF30aQm6C5Gh7BfNy4b6dykfv9Z5hUJ7kMWTpAUTRXyD5T9/pfT97DaNq4faIsz93OoTJDcsjfQGDomuiEJrodVZdRnvJLD53ANvbuhUio69OSjvUxiiNX3RYZCv8afBiqyHMQPWliVLGM0Q7j7Mc0vgIzkZvTKAmw4mrCyiytvZtEXegf3HFnwRQKyZdjo5oFkHziss8ilqJNls10QRN7dV+guuRiSap1O/YlswM9FT0FYwHfciSR9Dnqze6XfudIz25oq5MKnAAPnLqUCtELjAE5uWyfpQLYJaZc1hR+dOEobJVQ/yvCm8nm+qpmlCQpoyer04CS+FPeijk1Wso1LsTNWu9Nv1+VVsmZw0IhDi6YeGPun4T5teE0G2oMwBwAxgyekIVaQdiu++Kk4lHoEO16hCXGJ1PhxO+gH47NoM0rXZIMHLh/6cKx9rp8Ah8Tq2UevmeKYc0GOalMQNpaazIQr5+ZhH7KNSv0ZBgp0R0DYtTwuLICB7amz2Azt9+gO/asRFMJqyvUflFdjCYbUBxWnUrpyEy1iqEXDnK1H4+AA1WNNi55+Zpr/A36kxlTEWTQIrsWEYrtGGXM776dVfTpn9pL7ZWaX3h66gHD+xeKZXFtrhUPUv7ga+jb+Go+GByI36SkZW2aWgoCslTjZLJttb8zxAebOK0QRWvv067d3UuLtvmzfKu6v4pJ5i+Zxr4b8upH6gJBQt3bvlONidkn4KRPWuR+Igz9P7x/OkeX2QR59fzfvHS5bgZgRBHNyz8jVFJkkASo/DDFR0t4X0NYIKUbAu44PvHADLMx7WQ5QOznZFiOiI1DZZteJI9ghaR31cFEjo8T56utt1h8iYNAgl7ruarXaPJSb0tagCopXfKoJUBL4PXcYuOQ2SsVhMHjwyOit+1QSn1Q23l7wxGXuGPOdMAxdLX0noGWTVZbbMVMfVVdcVUrTuW9U05gNJK204qKA8SvjiQPy3TU2aMu+Xkkm56fudIrzUYsdG+4YT2W+jYyYonb7lUQ2B2LvNHPRzjt/FYjXGk8scLvmfmFP5qIv2No9Xioa4xJPUxZBiOvGGs05whzrqV3uT75ZYt500IhDi6WeGvVtAPIB/9AZfFY7WCD6v+XSGHTTQvQiuH4fs+tKMmMhKxdSz2d8UzaNWEf6KNyHyqXoumrw72po3dXg7OTvqa4FYba3q7wApr8+LYlTzLHw9reThlECY2P+f5LToNkbFaTdPP7sTOnCPen0c561P9dF1tSbl6BssZhL8e8OqTMmxHuTKjMugX++cpFBOcsbqCHtOYSa3t74ChHU12Z+3bmdNzDcYfMMiOZtxeoDbK7+xc5lj5BDm/D6A4VxHA7vuO6fk14jbjaYUvqCF9XH6ZVS2uPFOTVJoQlpftkRqHmsZbqsN8k+vF3i9bIzmYgkCIo5sT/sbyuUMruZnU/5zgppVmcFMDrxq82acrKgnukf8CF6PvoB2V96pCweSLq8jxW8hxttuohSBSN5De4g++7gAAGL5JREFUCOblhL8po6auvYLx6De4vpPC32U19QMbXMxgNZu1v+f5qcIfJ2Vo6Ke/WClrxAWnT3OF/CLh73KYto1I5a/P21YrUJaij7Cs+546uOnofNb0NCmJoX1yAk8O+zD2NYWyld8aAqGBtZbYXpgm/PVCoDqxpL5iYxAfB23evgPUoB3DU/ok25cEr1mblGZtrBLUdsLqZrTJ98stW86bEAhxdHXC36g2y31oqg4K4wH0s8P698P0DDqXcJxP6KdJSBvjNqC9cLN3ShMI7ifg+lc47b+Ff4xRK2BmsXYvi1S1ZvA2WgO791UxgKL60yeJ5d6VunM9gtNiDDe00lKTh89QMTJE1T/t+/OZeE2Y+8rALZIz6L/56Fn5u8LHDCjtFzAavoBcWQiX9d+moxAZw/X0DC5g9hWV7cRn40+i6QsSUkuWA6hedZAQJnUrfcpH3z2X6Xn99GSS7Af4HTzGupIa33BYTeyuYTLsw0nnAcRKC/UnTEYvIaNvsd1siO/cNqSWhl8w78es6Ym71oaG5yXH0xBYjMv0rjZMtlSfcJW/qYUa6+ibfOPYqrZYcGuMfMgh6//KPiPFaz02RqC/iQJyNEau8AYN/X6CEfoIwFdj8hZ66SPIR5/cQsz5Jt+vhirI5RoCIY6uQPjToMxUTnZfloQ33WNW2CQAuVqXC0jVDBo4H0H2hKyxjdEbNbPJ2p9msqieTZ/Du+H30Inx+L/ASfrvmZ3AERSjV5DaepBdABWAvziB4Zb4fCJAExJsI05ihjDI25BkfRi8P7dfA2AnqO9r3XbbNrtltCFDa/8vzGhQ5dGHIsfv3QlTXAn/W7mNwj8t403YkuMQGcNVJJ6xlT8+YCd2hH/Vg5nO0+VhAsd5Bi2LYQSt4xyOzZcbJbaEcZUTWvDTPfx16oTVGp/CkdEY0OQyilPIz8dwpfxb4HO4z/pSD7DXQ+h1C3h/zj6vwi9b8sIOwKq5alJL9jJfq59jedKHMTUD9lQhEs7lrt6dm8tK0zSNN31oV1T+JbpaAOMXQ9j/XSjGzlcpZVJ0sgJj+2UQL7O02Lc8Rl4WjqdJNn5qnvYDn/lt/v2qNFVOGhEIcXQFwr+x3BXcMKQi47kV5ChZ3C4CITLebs1WXLoysKIvFabl/QlGvWeOMVboGRTaT2WPPgTRBu7dGS5vAEspYj0IhDi65cLfVW+vByDJdXMIhMi4uVpspiS14m8/0+5Vm4pUmovu9D1Z87z2fdGD3rQ93Kby5PrKELhLXF4ZaJLRRhEIcXSLhb/ZGyPVrKz+N0qadRUWIuO6yry9fHErp4AsOYSsX1TVpujt7/ULdc/Gx7i9ikrJCyBwt7i8AEDyyK0jEOLoFgv/W8dNKrAGBEJkXENx25GlFfTGWZOa0OpPUMmgajsqKrWYB4E7yeV5AJK0t45AiKNe4Y8PyJ9gIBwQDggHhAPCgd3mQNMMxCv8mxLLdUFgWQRwIJF/gsA+ICBc3ode3O82hDhaG4lDifcbJmndJhAQfm0CZSljEwgIlzeBspSxDAIhjorwXwZZeXZuBEJknDszeUAQuEUEhMu3CL4UPRMCIY4uIfwda3xuJ4Cxnwdj41XKdQCh90+0O1xy3FLuqZRucmdqmyTaMQRCZAw3hdziug51uDOTJk+R4Zxnu+txsTrbg8ZJ1Bso+pkJx2z4ju/Ja8e5inIohV8IkHHgtDbRFwXT0nvew8oXNM5963xq5kbeuYSr57Lx68/G0qqb3xVCXHONPWveyLdZuYwhCFi4bOXUqoBxYzC3WbmMTk8xrkcpN8qgbbod1fvumDFrW3c/XYijSwh/BIYGRPKAxjuPhS91BrSqgDcTAO6id/cxlxY0IBAiY8Mj6vLN5BwwXHPVm55x72s81Ok0Te59Q7nPcI9cSc/rCpc8ENYEPbpV/QH6WRtiFlXy5vI1dLtmgLRe1vwuhrHW86Vn3ih9PtorLmRnwOSOJ1ktlxFM9GuyiQBL5r1B4enjQVO/zsllFb69e2w8ERL3mDttp5z5uFyGcI+8wd2462/totgp7k6chji6pPCnGRgJf8STJgQRVIU86yzmTlS7PuUThV3sE1yVPofMxmPfxTZsps4hMjbWQAmlBzoCI3elq6JEtljQG3JX24XB1Wqj1OhIa/chuU++/xtrW95QwvshpL23MGmszhVc9I+gnQ+Z//UyC1AuYZuFP0upD6elJ3/+3kE/EF2wVpBcWCmXceQc9+GwMcDTCvFWHDiAJLkHfsHpKWsVXFbRRw/Y++oph1+axmUbptv3fqAcOoHuFsc54U1d13GIo2sU/r4ZHqluI4gxiM7VEPJkTSu1daHpyVevOA8gFeHvQad6KUTGako6wxn8N9DO38K4OKqs/LVqj088fZNRymeZX5xUYHS/n+Gi/xCiiAJEhfI09eaxFvB7/1Ot+ler/ckFnOfHcHpxAcXRsWfCoifSrYaAU/XSZ0lPk/N6G3AiftQdQMhjfL3Mu3tllVy2YZ6VKhtjPryAongTUJEvjjtF57u4wOBnodDUVMYquIzhBgaQtR5DcTnLSnwWLps8MWaLO2lS7rV97xS16W78hji6YuGPqsyXer+yEiGKA42xpQ8hilqQJPchaVrx8Ecwuhnliy+HCpAyggEFuFF7l9x+wAiE6zEMznJI4zY8yR5BjM+m38E/D15Bnt6D5MkTSGPcN8I9oT9hfN4z5xg4I4PT0QT1GDBW6e9D2v8RiswEGDLts0Fb1EsbQVTZR600Qk4AlP+IeYDQLnIxzOgXmFSEP/W3M+tXqwUWQIoKs1w4grPRG+hhFDPcg0ThfMX2JeNO3ce+2h/V5ehIgJ7BhsqhX9RKtJ+WAp1U+Cogyye4HvX0/r9agWNbMsgqqxTkXR+y5NGMPvznSG+iaaoJuNVI4ATnyKkDNUZ+fQiEBlZf+mYus9TI06KAszyFuGmLaRkuq60FEyKatEANgYRsrZbmMm4H68iu9fDYthR2MAeXVXvuQcS0yZjRxrQorNbbeBji6IqEPze8QM9lg/CM1e6fzqLuN9oCOyibyYMi7B8wyO4xgUurGhT+f4cRTQ4iCglMK0OsLw/Hqsto094rDdTxY/jb+f+rZscIIkYHHE6+KGJhuGBL5CaBs41suOU6hchYq5qavVNwHBL2ZLzjnpunvX1htgNoVaVW42ZPkPeribZXXUW4K5DZ4k18HfXggYnqBxR6OGJ8V/UsOfR19C0cWc2RY3znDGw1nGDe9IQHmzihIDhkk5V6IXLFQWB1XHYyxlMSzDXDS+o7PobNymV39U3jZV0LxGu0HJf5mIt1PoBO8TvYOScvSB3Py2UykizfJVDbATKRRThDHF2R8Edhe2VWM/GU1byJk54kkOCqO8FVXTMVQO0TtepqHU4UttquqoKJSCQwNNN0Gr46NAM6rd7tr34paulNWF5r0+AVOLos+b+KQIiM1ZQ4oGVwZAcKV9i75+bpxr6gQZNxoZbWfMHCB1w1UW2zFfEsAyaW9Q3ko2tdKVppW9Uk5UHCF9vytExPQNgVXt1+hpJUfudIrzUY9K7i5Pdb6NjJSiVXOWlAYHVc9hVg+Oq1zViQy2YS2rI8DKjNbZVWxGWrQT1gizVbSP1gDi7biRLJEtRUdE5hHBIr9RL38kqIoysU/jjQ0QyUrXBcSJWR1gPIR3+UMehDqn9X0FbyM8J9WeGvZtnccKxSiPmshE0W3DrVhEj1eTkrEQiRsUyFR4FPSSMtDD+rz31m3fP3TBZq/VYX/qTmx3q7f1UNAa898vIpFJOvzACWBD2mM5NNO7AHDO0aV4C8PHY8c3quwUAN2iaszFk99+BwlVxGprj/1KLDcoTfXYzLVkh6uBw1qv5XyGVroMcm4LxZ7vHMXKbJNC7W/oCrwVM4lImsQjPE0RULfxzrfoeicwCRb8/fWIxatQ+l5epQlwAkBLwvwYqEP2kXXMOq699gNL4S4V/rk8UvhMgYztUz4KkVtavuewj+gczz/FThj6seNPS7cNSUXHD6lhd8wHQ5SkavVG+z5cRXYxUgsCyzR1u53nQya3oaMGNon5zAk8O+rJSaIG24vlIu18po4h4mXITLRj1eG0eJB02q/1Vy2ZRVq0Ot8ebCrFwuNRhR+ynkT2QiS4iGOLqk8PcTxxrBWaO50uBDGVjx8dKoRKOoyZkJaRMO2CdTOGCeQTH+BGNlfa01DTeTt8aQC1dpfN+/OtOsqfGtxoKXcQUXpy/hzdVNXfi7alwlRHAwfwvD3vPSyIt6QH4tAiEy2kTeA8+AR/2mJpqfTfjcpq9HSFVarsBJ9W2FO6001OBktqfiMj2vluYQtxup3GVqfCP81b79NUyGfTjpPIBY8fNPbciaHsNg4rOANt9G+ybSvDh7PGd6ai+3X7F5ycE0BFbKZVRzW4dPX2AyfA5pu2lLdF4uo7OdX6Gf3vNMZHEuMYK8hVuwzzw8xPeOtqSW4TJ96n0Is4WwnpPLVqswp++CaZ284/dDHF1C+HvUsnavlAR2XVWKVv72kzgiHVdD2Tw46ldVS/yoFNKl8xf8PKaA94MTaCkPg+xrAJW/ngDoQZvqxeqCe1Iea/8vFU9SLUhfvdIvCtUZ62s1GKVhIa+9HJcIhMhYpvId+YQ/apomMOyhZTT2adME0gxa1GdRAsd5VvEQ1jrO4RgHQJuGH/u2Fvj96uQSa38zPoUjozGwk2H1lcoYroxhoTI6zV6CCut7PYRet4D3513TFsz/ANK80PcNJHYbQu1vfoWrQTi9D8nymhEiUw0KyyfkqERglVwuxzHs95DR9LJcduxHamMwHxN1Wxfj8mu4/McAMvU1lX5X4jSHQn1BRfnqTw213deyXCbDv2kGhWX/3YWjEEeXEP53ATpp46oRCJFx1WXdan44ITyiLxWm1eQTjHrP6p8YNj6GQvvpjJ8ANmYiN5ZEQLjsA1C47EPltq6FOCrC/7Z65Y6WGyLjvkGiv+v2qVJZS5XmogtPB5eOXQFLww5vJiN43e9Bb8b07FE5XDECwmUHUOGyA8jtn4Y4KsL/9vvnTtUgRMb9A4JiXRxC1i9gMGa+89Db3+sXkCWz7oHuHzq73iLhsulB4fLWUjnEURH+W9tt+1mxEBn3s8XaLkELeoq8R/u6P1T28/e2/XvaMOGy3svXNgrC5W2keYijXuGPD8ifYCAcEA4IB4QDwoHd5kDTpMQr/JsSy3VBYFkEcCCRf4LAPiAgXN6HXtzvNoQ4WhuJQ4n3GyZp3SYQEH5tAmUpYxMICJc3gbKUsQwCIY4uIfzd701JNYLf2/erxk3L1H5tz1LkqHbdp/raypSMQ2RcFzrKQl5Fd6x/j79UmTUPg0vlJg/vGALzcZmMP8nuo8knBQeBnPnQ2NrkhY8/M8ux8VA5s6e9WfKUNNuIQIijSwh/bCp5+CMnKMYzFTp22HLHIaWzH6r7Nnbd/tUpRMb1tJY7o1ql8GeOrGQQXU/XbXmu83D55vI1dLuFjnZKUUMjv/dI22ycXK7B7bJ1OjWtfFsROdhVBEIcXVL4U7hGLkBpUCTf5dsLm54A8Lpvb11vv2YYSvnYBKtZvDYhMi6WK66o3kDRz6Dd6B+/wTvgYgXqp5Rr3ANIknsQySC6DJI7++xSXFYuwUPCH1f96whLq7UJcZLAfXHrvLPcm7XiIY6uQfjThMBxIzlrbTeYToT/rGAbP9vR8ivnEBlnrY1Kh77QixeQtTuQn/045ZO51Qt/5Wa33YeLC+2itDnC31ytksQ7hMDiXNYa05YbSIy33cY8QZU/uvs9g2IwBhMkmqec71hNWh9B/+Jn6LfjhiBY82UpqbcXgRBH1yD8aSvArPzRAcRpBgl9PmiD/XCbAfQn/R5GeVJ+Yqh8/LM0eH49hvOc/LijbQH5RR/DQO3ptuFJ9kj7Rm+KEVB0TV0obbnyv5kM4TRrmzqw/Cv+r4+g+PCO+fc3vrBtmr9A8p++gzOsZ/oCBqy8UECLatno0/0nGH8a2nJa+Qi+UoRDxFKFMdarXlVW8hiy9ABU7IT+f/PjMRW/DvQHryBLcF+SgtaQJof2HZeb1IXIOPUVUs5Evoc8fVh3mhN8eBbhz7imsKVnsN0lR3QxLNoYBcdpDIkarJjc3GEEFuMy2Ro9msE9s9FqFch5fLd9moJ5eGvGZrVNRfYEq7Ij2OGO3OOqhzi6IuF/AGn/V7gGZtSi9vz/gFF+WEaLsntdOgofUCQmO3BSuNOS5Lg/ddQdwBWg2vmRKYciRMUQd/pwdkKThlBgHSPE4o72oW7rYgb26yHkSQso6qANtKECqNwAxcIuV3hYn0OI7H4v5t+F7vl/1zNqFNBxCr3hBG5IQNi0DttU2fdKDEc9SCLzUpoVgBb++Jwx1kEB9dlE48KybEQuNhhEHI8m/F7C+XcPzYSHAibRwED9QILwNlf+pl3eSZ2DZ+101vozbFWAdZrIOsIf+6T1GIpLjMRHaWQQrcG+5xdCA6u/6fzdnM8uSgd0qgfd0eXMyFs1drTBhlQ3Y0s5pvlrLVd3F4EQR1ck/MtVIRYWpz04R1emilzO3r8hXGQGcU1qGjhpIKVncNDOIBt8NHlVy8GydOz2K6M1CAgnT11Ktf+ViY5Gwg47m+pCL5wRiHaiYl44Oxv/AEXnmQ7nS1oAK6jMS69WlC6RjGCy+Tr3TV6l8HfyqpWFz9Mgw/Ag3BEz/qfKreNXYoOKxlmFp1N3z2mIjJ7k1UuVlf8ZvGYRwqoJ3bNZ6+9gq6Kd5tCqrPz1JLLF7QsMtjKIurjv9/nCXMYtK6WpnEOLphYQLX9IXnrf2fhSfX91PyhDv1aXhRw3Y1jT2LPf3XcnWhfi6IqEv7MyMrBqApLwJKyN9TUR1ayK9cD5EQbdLuQnD4xQ/wMG3RNFVj1J4MKZ8sNfj7Djt1GUj3FvtlqX8gX5u3/yoIxyyhe0MlG5GkA3O4GTdgyq7niuNBQsPvZMwr8ucCpVX5Hwnxe/EpstEv4cmLXs+df7oooDEumi1OzwSZSdiN7wWsrxHiMQGlinNpt4ZMeIaU8gN9tLCH/S5jmTf8VhWnxNq4Pc3zUEQhxdq/AHIzwrK6KKsEcoyxX1+bAPnXwIV0pQ34Ps7GUpUFVebqxm3Gb4BcbX9ZVrrZPU86RR0Hf1wI7E/ztMiiOISNVuHq4Ie7xm6/4DDPsZ5KMJjPsPIYozODs7hi5qKPBfbTVeFyo6oUpsym6Y2KxI+Ou+mB2/qtCbdeVctqrpKETGpmfC182+6Eqs/ev9VMXBTCJr2zekJZJBNNxX+3V3OS7jqvt+gzD34KTGniY7gem81WOX53nRWnnA3p9LIY4uKfynDXpmXxytVYsLuAayGqc9fw0yrcqT5EgbwdCsmAtjjI/eOSj30fHR61/htP8WrmZY+YP7vN3zx5lwC9L+95CjoVvShQK3LOg+7fmrqtJE5T4k6SmM0RRATVRo+8Gs+mrCP6xeo+9u4/Q5DCe4j4xtG8FpMS7tBVQ9PsNk+BxS9KOAM3a+719ZQZjBgFvnu+1XZTTh5/YrCf+H0B+9gV7+Blh8Ol3fGf8PkXHGLBZIxuo//hx4nlZHmp83k7fQU4ZWiHcC+eB/QD+95x+wqc+t7UWgGLm1FwgszmUzDjZyRU9o7baWCpXbgXY+bLD2n8Lb0SVc9DsQ1yat2A00VnD7oL3oHmkEgJITTUAsIfyJNKUaqdyXZsUp4pKFPhqmZXDq7tXSitp++kJClu9PIU991v5/Vr8S4AKPVQMPKxb1cQf++uIJtJIM+q9HMEFBXhnsmbU/y0cLe7aCprrTHjAJAVIJp30o+FcM3vrhy/6TsejVeJYTAZow4XWcRA1hkLe1F8X35/ZrADUZUBMAt1/Yvv+M+L0qjqFF9TdbJTRBKQ0LGShzHC4+YM5RSCUpd/KDGFa3fipJFUfOoUtfO2QFvB+caI781Ies1cB1t8+nlOGWKee7icDsXKbJNPEHv+YpKp+n2kUETfIHzypfSPWnfOZnDZTxKx3O28EIBnz8oe1WBbk7VkRAtli72SNSaxeBEEeXEP5uMXIuCExHIETG6U9LCkFgexBYPZdx0fN0hk8AtwcDqcl2IxDiqAj/7e67vatdiIx711hp0F4jsEouq/gT/R70BpcgJqN7TZuNNi7EURH+G+0KKSxERkFHENglBITLu9Rbd7OuIY6K8L+bnLi1VofIeGuVkoIFgQUQEC4vAJo8slEEQhwV4b/RrpDCQmQUdASBXUJAuLxLvXU36xriqFf44wPyJxgIB4QDwgHhgHBgtznQNO2pCf+mhHJdEBAEBAFBQBAQBPYDARH++9GP0gpBQBAQBAQBQWBmBET4zwyVJBQEBAFBQBAQBPYDARH++9GP0gpBQBAQBAQBQWBmBET4zwyVJBQEBAFBQBAQBPYDARH++9GP0gpBQBAQBAQBQWBmBET4zwyVJBQEBAFBQBAQBPYDgf8LlRAEMs/JlCAAAAAASUVORK5CYII=
