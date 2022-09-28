//
//  CourseScoreUIView.swift
//  trombonius
//
//  Created by danonya666 on 27.09.2022.
//

import SwiftUI

struct CourseScoreUIView: View {
    @AppStorage("score") private var score: Int = 0
    var body: some View {
        VStack {
            Spacer()
            Button(action: /*@START_MENU_TOKEN@*//*@PLACEHOLDER=Action@*/{}/*@END_MENU_TOKEN@*/) {
                Text("MenuItem1")
            }
            Spacer()
            Button(action: /*@START_MENU_TOKEN@*//*@PLACEHOLDER=Action@*/{}/*@END_MENU_TOKEN@*/) {
                Text("MenuItem2")
            }
            Spacer()
            Button(action: /*@START_MENU_TOKEN@*//*@PLACEHOLDER=Action@*/{}/*@END_MENU_TOKEN@*/) {
                Text("MenuItem3")
            }
            Spacer()
            Text(String(score)).font(.system(size: 50))
                .foregroundColor(Color.red)
                .padding(.top, 100.0)
            Spacer()
            HStack {
                Spacer()
                Button(action: {
                    if (score > 0) {
                        score -= 1
                    }
                }, label: {
                    Text("<").font(.system(size: 40)).foregroundColor(Color.red)
                })
                Spacer()
                Button(action: {
                    score += 1
                }, label: {
                    Text(">").font(.system(size: 40)).foregroundColor(Color.red)
                })
                Spacer()
            }
            .padding(40.0)
        }
    }
}

struct CourseScoreUIView_Previews: PreviewProvider {
    static var previews: some View {
        CourseScoreUIView()
    }
}
