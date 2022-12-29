<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Decideitor</title>
  <style>
    body { font-size: 2em; text-align: center; margin-top: 2em; }
    #nOpt, #opts input { width: 100%; border: 1px solid transparent; border-bottom: 1px solid #333; font-size: 1.5em; margin: .5em 0; text-align: center; }
    #opts input:focus { border-bottom-width: 5px; outline: none !important; }
    #btn-decide { width: 100%; border: 1px solid transparent; color: white; font-size: 1.5em; padding: 0.3em; background-color: teal; }
    #btn-decide:focus { background-color: teal; color: white; }
  </style>
</head>
<body>
  ¿Cuántas opciones quieres?
  <input type="number" id="nOpt">
  <div id="opts"></div>
</body>
<script>
  let nOpts = 0
  window.addEventListener('load', function(){
    const _nOptInput = document.querySelector('#nOpt')
    const _optsContainer = document.querySelector('#opts')

    const decide = () => {
      const choices = {}
      for(let i = 1; i <= nOpts; i++){
        const d = parseInt((Math.random() * nOpts) + 1, 10)
        if(typeof choices[d] === 'undefined') choices[d] = 1
        else choices[d]++
      }
      let maxOpt = { key: 0, val: 0 }
      for(let key in choices){
        if(choices[key] > maxOpt.val){
          maxOpt.key = key
          maxOpt.val = choices[key]
        }
      }
      return maxOpt.key
    }

    const genInputOptions = () => {
      for(let i = 1; i <= nOpts; i++){
        const input = document.createElement('input')
        const label = document.createElement('label')
        label.innerHTML = `Opción ${i}:`
        const container = document.createElement('div')
        container.appendChild(label).appendChild(input)
        _optsContainer.appendChild(container)
      }
      genDecideButton()
    }
    const genDecideButton = () => {
      const button = document.createElement('button')
      button.id = 'btn-decide'
      button.innerHTML = '¡Decide por mí!'
      button.addEventListener('click', function(){
        const d = decide()
        const chosen = _optsContainer.querySelector(`div:nth-child(${d})`)
        alert(`Decidido: ${chosen.querySelector('input').value}`)
      })
      _optsContainer.appendChild(button)
    }

    _nOptInput.addEventListener('keyup', function(){
      _optsContainer.innerHTML = ''
      if(this.value){
        nOpts = parseInt(this.value, 10)
        genInputOptions()
      }
    })
  })
</script>
</html>
