function createSlides() {
  var presentation = SlidesApp.create('Histoire de l\'éditorial');
  
  // Ajouter une diapositive avec un titre et un contenu
  var slide1 = presentation.appendSlide(SlidesApp.PredefinedLayout.TITLE_AND_BODY);
  slide1.getPlaceholder(SlidesApp.PlaceholderType.TITLE).setText('Histoire de l\'éditorial');
  slide1.getPlaceholder(SlidesApp.PlaceholderType.BODY).setText('L\'éditorial est une pièce maîtresse qui exprime l\'opinion d\'un média sur des sujets d\'actualité, politique, etc.');

  // Ajouter une autre diapositive
  var slide2 = presentation.appendSlide(SlidesApp.PredefinedLayout.TITLE_AND_BODY);
  slide2.getPlaceholder(SlidesApp.PlaceholderType.TITLE).setText('Les Origines de l\'éditorial');
  slide2.getPlaceholder(SlidesApp.PlaceholderType.BODY).setText('Les débuts de l\'éditorial remontent à la Gazette de Théophraste Renaudot.');

  // Répéter ces étapes pour ajouter plus de contenu à ta présentation
}

