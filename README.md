# Multiple_and_polynomial_regression
Comparison between multiple regression and polynomial regression
<p>
Pour comparer les résultats des modèles de régression multiple et de régression polynomiale, nous pouvons utiliser certaines mesures d'évaluation. Les mesures couramment utilisées pour les modèles de régression comprennent <b>l'erreur quadratique moyenne (MSE)</b>,<b> l'erreur quadratique moyenne racine (RMSE) </b>et <b>le coefficient de détermination (R^2)</b>.</p>
<h3>Les résultats de y_pred de la RM</h3>
<p>Voici déja le résultat de la régression multiple : </p>
<img src="MReg_result.PNG"/>
<h3>Les résultats de y_pred de la RP</h3>
<p>Voici également les résultation prédits par la regression polynomiale</p>
<img src="PReg_result.PNG"/>
<h3>Les résultat de y_test</h3>
<img src="yTest.PNG"/>
<h3>Les résultats de RMSE et R-carré</h3>
<img src="comparaison.PNG"/>
<p>Selon les résultats que nous avons obtenu, le modèle de régression polynomiale est meilleur que le modèle de régression multiple. Voici pourquoi :</p>
<ul>
  <li><b>RMSE (Erreur quadratique moyenne):</b> Le RMSE du modèle de régression polynomiale est plus bas (149 886) par rapport au RMSE du modèle de régression multiple (208 139). Un RMSE plus bas indique que le modèle de régression polynomiale présente en moyenne de plus petites erreurs de prédiction, ce qui suggère de meilleures performances.
  </li>
  <li><b>R-carré : </b>La valeur de R-carré du modèle de régression polynomiale est plus élevée (0,811) par rapport à celle du modèle de régression multiple (0,636). Le R-carré mesure la proportion de la variance de la variable dépendante (prix) qui peut être prédite à partir des variables indépendantes. Une valeur de R-carré plus élevée indique que le modèle de régression polynomiale explique une plus grande partie de la variance des données, ce qui témoigne d'une meilleure adéquation.
  </li>
</ul>
<p>Sur la base de ces métriques, le modèle de régression polynomiale est considéré comme meilleur que le modèle de régression multiple pour ce problème particulier</p>
