<template>
    <div>
        <main-nav />
        <img src="@/assets/img/privacy_policy_bg.jpg" class="banner" />
        <div class="main main-raised">
            <div class="section">
                <div class="container">
                    <div class="md-layout">
                        <div class="md-layout-item md-size-66 text-left md-xsmall-size-100 mx-auto text-center">
                            <h2 class="text-left">Politique de Confidentialité</h2>
                            <h5 class="description">
                                <h3>Données Personnelles</h3>
                                <p>
                                    Aux fins du déploiement de l'application, les "Informations personnelles" désignent toute information fournie par les utilisateurs ou collectée par Agro Innova dans le cadre de cette application, qui fait l'objet de cet engagement et qui :
                                    (a) identifie ou peut être utilisée pour identifier, contacter ou localiser l'utilisateur auquel ces informations se rapportent, ou 
                                    (b) à partir de laquelle des informations d'identification ou de contact d'un utilisateur individuel peuvent être dérivées. 
                                    Les données personnelles incluent, mais sans s'y limiter, le nom, l'adresse, le numéro de téléphone, le numéro de fax, l'adresse e-mail, le numéro de sécurité sociale ou tout autre identifiant délivré par le gouvernement, ainsi que les informations de carte de crédit. De plus, dans la mesure où toute autre information (telle que, mais pas nécessairement limitée à un profil personnel, un identifiant unique, des informations biométriques et/ou une adresse de protocole Internet) est associée ou combinée avec des données personnelles, alors ces informations seront également considérées comme des données personnelles.
                                </p>
                                
                                <h3>
                                    Collecte et Accès
                                </h3>
                                <p>
                                    Nous garantissons que nous ne collecterons ni n'accéderons à aucune information personnelle, sauf dans la mesure où cette collecte ou cet accès est strictement nécessaire pour exécuter les fonctions de l'application ou pour répondre à toute exigence légale dans le cadre de l'exploitation de l'application dans la juridiction où elle est autorisée à fonctionner. Dans toutes les circonstances où des données personnelles doivent être collectées, Agro Innova fournira dans l'application un avis clair et visible concernant l'utilisation des données personnelles et respectera les exigences juridictionnelles, les avis, les politiques et les procédures relatives à la collecte et à l'utilisation des données personnelles.
                                </p>

                                <h3>
                                    Utilisation des Informations Personnelles
                                </h3>
                                <p>
                                    Agro Innova utilisera les données personnelles collectées par l'application uniquement dans la mesure nécessaire pour exécuter les fonctionnalités de l'application, conformément aux termes du consentement préalable donné par l'utilisateur, ainsi qu'aux lois applicables sur la protection des données de la juridiction spécifique. Ces données seront classées comme des informations confidentielles et protégées en vertu de la loi générale sur la confidentialité. 
                                    Agro Innova s'engage à ne pas partager les données personnelles collectées ou en sa possession avec des tiers pour quelque raison que ce soit, sauf si cela est nécessaire pour le fonctionnement de l'application, et uniquement selon des conditions acceptables pour l'utilisateur.
                                </p>

                                <h3>
                                    Traitement des Informations Personnelles
                                </h3>
                                <p>
                                    Agro Innova prendra des mesures raisonnables pour protéger les données personnelles en sa possession contre toute utilisation, accès, divulgation, altération ou destruction non autorisés. Les mesures de sécurité comprendront, sans s'y limiter, des contrôles d'accès, le chiffrement ou d'autres moyens, le cas échéant. Agro Innova effectuera un audit au moins une fois par an pour évaluer la sécurité des données personnelles en sa possession et vérifier que les termes de cet accord concernant les informations personnelles sont respectés. Sur demande de GIZ, Agro Innova fournira à GIZ tous les résultats d'audit et toutes les informations personnelles en sa possession.
                                </p>
                            </h5>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <main-footer/>
    </div>
</template>

<script>
import MainNav from '@/layout/MainNavbar.vue'
import MainNavbar from '../../layout/MainNavbar.vue'
import MainFooter from '../../layout/MainFooter.vue'
export default {
    components: { MainNav, MainFooter }
}
</script>

<style>
.banner {
    max-height: 400px;
    width: 100vw;
    object-fit: cover;
    object-position: 100% 20%;
}
</style>
