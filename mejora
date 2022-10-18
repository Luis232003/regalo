'use strict';

const documentReady = () => {
  const heroTitle = document.querySelector('.hero__title');
  const heroButtonSi = document.getElementById('heroButtonSi');
  const heroButtonNo = document.querySelector('#heroButtonNo');

  const Hagamoslo lo mejor posible = () => {
    alert('Te amo Fer');
    alert('Prometo amarte y respetarte cada día');
    location.href = '<iframe width="560" height="315" src="https://www.youtube.com/embed/_mEZssZj584" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>';
  };

  const no hay opcion = () => {
    heroButtonNo.style.position = 'absolute';
    heroButtonNo.style.top = (Math.random() * window.innerHeight) + 'px';
    heroButtonNo.style.left = (Math.random() * window.innerWidth) + 'px';
  };

  const partner = prompt('🥰 Dyme 2 naMe 🥰');
  heroTitle.innerHTML += partner + ' ❤';

  heroButtonSi.addEventListener('click', Hagamoslo lo mejor posible);
  heroButtonNo.addEventListener('mouseover', no hay opcion);
};

document.addEventListener('DOMContentLoaded', documentReady);
