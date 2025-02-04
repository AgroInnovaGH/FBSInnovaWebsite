<template>
    <div>
        <main-nav />
        <img src="@/assets/img/privacy_policy_bg.jpg" class="banner" />
        <div class="main main-raised">
            <div class="section">
                <div class="container">
                    <div class="md-layout">
                        <div class="md-layout-item md-size-66 text-left md-xsmall-size-100 mx-auto text-center">
                            <h2 class="text-left">Privacy Policy</h2>
                            <h5 class="description">
                                <h3>Personal Data</h3>
                                <p>
                                    For the purposes of the deployment of the App, “Personal Information” means any information provided by users or collected by Agro Innova in connection with this app which is the subject of this engagement and which:
                                    (a) identifies or can be used to identify, contact, or locate the user to whom such information pertains, or 
                                    (b) from which identification or contact information of an individual user can be derived. 
                                    Personal data includes, but is not limited to, name, address, phone number, fax number, email address, social security number or other government-issued identifier, and credit card information. Additionally, to the extent that any other information (such as, but not necessarily limited to, a personal profile, unique identifier, biometric information, and/or Internet Protocol address) is associated or combined with Personal data, then such information also will be considered Personal data.
                                </p>

                                <h3>Collection and Access</h3>
                                <p>
                                    We warrant that we will not collect or access any Personal Information except to the extent that such collection or access is strictly necessary to perform the functions of the app, or to fulfill any legal requirements in the operation of the app within the jurisdiction that it is licensed to operate. In all circumstances where personal data will be required to be collected, Agro Innova will provide within the app a clear and conspicuous notice regarding the uses of the Personal Data and comply with jurisdictional requirements, notices, policies, and procedures for the collection and use of Personal Data.
                                </p>

                                <h3>Use of Personal Information</h3>
                                <p>
                                    Agro Innova will use Personal Data collected by the app only as necessary to run the features of the app, and in accordance with the terms of the prior consent to be given by the user, as well as the applicable data protection laws of the specific jurisdiction. Such data will be classified as confidential information and protected under the general law on confidentiality. Agro Innova will undertake not to share any Personal Data that is collected or possessed with any third parties for any reason except as necessary to run the application, and only under terms and conditions agreeable to the user.
                                </p>

                                <h3>Handling of Personal Information</h3>
                                <p>
                                    Agro Innova will take reasonable steps to protect Personal Data in its possession from unauthorized use, access, disclosure, alteration, or destruction. Security measures will include, without limitation, access controls, encryption, or other means where appropriate. Agro Innova will conduct an audit on at least an annual basis to evaluate the security of Personal Data in its possession and to verify that the terms of this Agreement with respect to Personal Information are being followed. Upon request from GIZ, Agro Innova will provide GIZ with all audit results and all Personal Information in Agro Innova’s possession.
                                </p>

                                <h3>Children's Privacy</h3>
                                <p>
                                    Agro Innova is committed to protecting the privacy of children under the age of 13. We do not knowingly collect, use, or disclose personal information from children without verifiable parental consent, except as permitted by law. If we become aware that we have inadvertently collected personal information from a child under 13 without proper consent, we will take immediate steps to delete that information. 
                                </p>
                                <p>
                                    Parents or guardians have the right to review, delete, and refuse the collection of their child's personal information. To exercise these rights, or if you have any concerns or questions about our children's privacy practices, please contact us at [insert contact information].
                                </p>
                                <p>
                                    The app may contain educational and interactive features for children. However, we ensure that any data collected from children is strictly limited to what is necessary to support these features and in compliance with all applicable laws such as the Children’s Online Privacy Protection Act (COPPA).
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