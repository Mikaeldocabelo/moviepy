.. custom module to enable complete documentation of every function
   see https://stackoverflow.com/a/62613202
   
moviepy.Effect
==============

 
.. automodule:: moviepy.Effect
   :inherited-members:

   
from moviepy.editor import ImageClip

# Caminho para a imagem
image_path = "caminho/para/a/imagem.png"

# Criar clipe da imagem
image_clip = ImageClip(image_path).set_duration(5)

# Ajustar para 1080x1080 com fade-in e fade-out
image_clip = image_clip.resize((1080, 1080)).fadein(1).fadeout(1)

# Salvar o vídeo
image_clip.write_videofile("video_anuncio_asad.mp4", fps=24)
   
   
   


   
   
   


   
   
   



