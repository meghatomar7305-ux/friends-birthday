import qrcode
url = "https://raw.githubusercontent.com/meghatomar7305-ux/friends-birthday/main/assets/animation.gif"
img = qrcode.make(url)
img.save("qr.png")
