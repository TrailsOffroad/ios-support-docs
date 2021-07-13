# SupportDocs: DataSource
This branch is where SupportDocs gets its data! You can add, edit, and delete documents here. For usage instructions, check out the `README`'s [usage](https://github.com/aheze/SupportDocs#using-the-github-repo) section in the main branch.

## Data Source JSON URL
<a href="https://raw.githubusercontent.com/TrailsOffroad/ios-support-docs/DataSource/_data/supportdocs_datasource.json">https://raw.githubusercontent.com/TrailsOffroad/ios-support-docs/DataSource/_data/supportdocs_datasource.json</a>

<details>
<summary><strong>Show examples</strong></summary>

<hr>

### SwiftUI
```swift
struct SwiftUIExampleView_MinimalCode: View {
    let dataSource = URL(string: "https://raw.githubusercontent.com/TrailsOffroad/ios-support-docs/DataSource/_data/supportdocs_datasource.json")!
    @State var supportDocsPresented = false
    
    var body: some View {
        Button("Present SupportDocs from SwiftUI!") { supportDocsPresented = true }
        .sheet(isPresented: $supportDocsPresented, content: {
            SupportDocsView(dataSource: dataSource, isPresented: $supportDocsPresented)
        })
    }
}
```

### UIKit
```swift
class UIKitExampleController_MinimalCode: UIViewController {
    /**
    Connect this inside the storyboard.
    
    This is just for demo purposes, so it's not connected yet.
    */
    @IBAction func presentButtonPressed(_ sender: Any) {
        let dataSource = URL(string: "https://raw.githubusercontent.com/TrailsOffroad/ios-support-docs/DataSource/_data/supportdocs_datasource.json")!
    
        let supportDocsViewController = SupportDocsViewController(dataSource: dataSource)
        self.present(supportDocsViewController, animated: true, completion: nil)
    }
}
```

<hr>

</details>

## Table of Contents
- [404 Page](https://TrailsOffroad.github.io/ios-support-docs/404) (SupportDocs Integrated File) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/ios-support-docs/404.md))
- [Can I use the app Offline?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/Offline) (faq, offline) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/Offline.md))
- [How can I update my Credit Card?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/AddCreditCard) (faq, account) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/AddCreditCard.md))
- [How can I update my Profile?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/UpdateProfile) (faq, account) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/UpdateProfile.md))
- [How do I cancel?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/Cancel) (faq, account) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/Cancel.md))
- [How do I download a trail?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/DownloadTracks) (faq, map, offline) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/DownloadTracks.md))
- [How do I exit Follow mode?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/FollowExit) (faq, map, follow) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/FollowExit.md))
- [How do I see my current GPS location?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/MyLocation) (faq, map) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/MyLocation.md))
- [How many trails do you have?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/HowManyTrails) (faq) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/HowManyTrails.md))
- [How to use the app Offline](https://TrailsOffroad.github.io/ios-support-docs/Support-Guides/Offline-Overview) (guide) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-Guides/Offline-Overview.md))
- [I lost my password.](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/LostPassword) (faq, account) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/LostPassword.md))
- [What do the Colors mean?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/Colors) (faq, map) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/Colors.md))
- [What does Follow do?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/Follow-What) (faq, follow) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/Follow-What.md))
- [What does High Clearance mean?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/HighClearance) (faq) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/HighClearance.md))
- [What is All Access?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/AllAccess) (faq, all-access) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/AllAccess.md))
- [What is the difference between the app and the website?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/Difference) (faq, general) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/Difference.md))
- [Where can I read/write a Trail Review?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/TrailReview) (faq) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/TrailReview.md))
- [While Following a trail why are waypoints skipping?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/FollowWaypointsSkipping) (faq, follow) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/FollowWaypointsSkipping.md))
- [Why are there no trails near me?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/NoTrailsNearMe) (faq) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/NoTrailsNearMe.md))
- [Will my login work on the app and website?](https://TrailsOffroad.github.io/ios-support-docs/Support-FAQ/AccountWebsiteVSApp) (faq, account) ([edit](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/Support-FAQ/AccountWebsiteVSApp.md))


## Notes
- Your changes make take up to five minutes to deploy. You can track the deployment progress [here](https://github.com/TrailsOffroad/ios-support-docs/deployments/activity_log?environment=github-pages).
- Do **not** update this file (`README.md`) directly. Your changes will be overriden the next time you push (the GitHub Action will regenerate this file). Instead, update the file in [`_scripts/README.md`](https://github.com/TrailsOffroad/ios-support-docs/edit/DataSource/_scripts/README.md). 