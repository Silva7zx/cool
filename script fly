local voando = false

function voar()
  voando = not voando
  if voando then
    print("Voando...")
  else
    print("Parando de voar.")
  end
end

function onKeyPress(key)
  if key == "e" then
    voar()
  end
end

print("Pressione a tecla 'E' para voar.")
while true do
  local key = io.read()
  onKeyPress(key)
end
