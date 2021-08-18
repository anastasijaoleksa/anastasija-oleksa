module.exports = {
    'cura.js': client => {
      let curaPage = client.page.curaPage();

      const personData = {
        contactName: 'John Doe',
        contactPassword: 'ThisIsNotAPassword'
      };
      const facilityData = {
        facilityData: 'Seoul CURA Healthcare Center',
        visitDate: '02/09/2021',
        comment: 'This is a test appointment',
      }
      curaPage.prepareWebsite ();
      curaPage.attemptSignIn (personData);
      curaPage.bookingAnAppointment (facilityData);
      curaPage.validationOfData ();
      curaPage.LogoutFromCura ();
      curaPage.Verify ('.Seoul cura healthcare center ');
      curaPage.Verify ('#program');
      curaPage.Verify ('#visit_date');
      curaPage.Verify ('#comment');

        // .navigate()
        // .waitForElementVisible('@textVerticalCenter', 10 * 1000)
        
    //     .click('@openMenu')
    //     .click('@openLogin')
        
    //     .setValue('@demoContactName', 'John Doe')
    //     .setValue('@demoContactPassword', 'ThisIsNotAPassword')
      
    //     .click('@loginButton')

    //     .click('@facility')
    //     .setValue('@facility', 'Seoul CURA Healthcare Center')

    //     .click ('@redmissionChecked')

    //     .click('@programMedicaid')

    //     .setValue('@visitDate', '02/09/2021')

    //     .click('@addComment')
    //     .setValue('@addComment', 'This is a test appointment')

    //     .click('@bookAnAppointment')

    //     .getText('@getTextAfter')

    //      .click('@openMenu')
    //      .click('@logout') // a[href*='logout'] - Darta gave

    //     .assert.visible('@notDisplayed')
    //     .assert.not.elementPresent('@notDisplayed')

    //     //npm test tests/curaBetter.js
    // }}
    }
}
