# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 18:17:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 3589.8 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113421
telemt_connections_bad_total 3471
telemt_connections_current 1558
telemt_connections_me_current 1558
telemt_handshake_timeouts_total 1077
telemt_upstream_connect_attempt_total 510
telemt_upstream_connect_success_total 501
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 305
telemt_me_reconnect_success_total 303
telemt_me_reader_eof_total 299
telemt_me_idle_close_by_peer_total 299
telemt_me_route_drop_no_conn_total 38190
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97772
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 447
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 315
telemt_me_writer_restored_same_endpoint_total 290
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 97980
telemt_user_connections_current{user="hello"} 1558
telemt_user_octets_from_client{user="hello"} 1615103764 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 32626150892 (30.39 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 20045.2 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1997765
telemt_connections_bad_total 97771
telemt_connections_current 3784
telemt_connections_me_current 3784
telemt_handshake_timeouts_total 37368
telemt_upstream_connect_attempt_total 4638
telemt_upstream_connect_success_total 4578
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 4638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6523
telemt_me_reconnect_success_total 2298
telemt_me_reader_eof_total 2480
telemt_me_idle_close_by_peer_total 2480
telemt_me_route_drop_no_conn_total 1146729
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1661209
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6729
telemt_desync_full_logged_total 2131
telemt_desync_suppressed_total 4598
telemt_desync_frames_bucket_total{bucket="1_2"} 1284
telemt_desync_frames_bucket_total{bucket="3_10"} 2684
telemt_desync_frames_bucket_total{bucket="gt_10"} 2761
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2444
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2243
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1661196
telemt_user_connections_current{user="hello"} 3784
telemt_user_octets_from_client{user="hello"} 24348668358 (22.68 GB)
telemt_user_octets_to_client{user="hello"} 538385866950 (501.41 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1274
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 20023.5 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1835743
telemt_connections_bad_total 219361
telemt_connections_current 2743
telemt_connections_me_current 2743
telemt_handshake_timeouts_total 19660
telemt_upstream_connect_attempt_total 3193
telemt_upstream_connect_success_total 3171
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3038
telemt_me_reconnect_success_total 2120
telemt_me_reader_eof_total 2160
telemt_me_idle_close_by_peer_total 2159
telemt_me_route_drop_no_conn_total 1586257
telemt_me_route_drop_channel_closed_total 100
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1394931
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4490
telemt_desync_full_logged_total 1340
telemt_desync_suppressed_total 3150
telemt_desync_frames_bucket_total{bucket="1_2"} 1165
telemt_desync_frames_bucket_total{bucket="3_10"} 1693
telemt_desync_frames_bucket_total{bucket="gt_10"} 1632
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 2111
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2119
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1391913
telemt_user_connections_current{user="hello"} 2743
telemt_user_octets_from_client{user="hello"} 18028874720 (16.79 GB)
telemt_user_octets_to_client{user="hello"} 438492246444 (408.38 GB)
telemt_user_unique_ips_current{user="hello"} 945
telemt_user_unique_ips_recent_window{user="hello"} 370
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 20011.1 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1703901
telemt_connections_bad_total 59262
telemt_connections_current 2910
telemt_connections_me_current 2910
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 23349
telemt_upstream_connect_attempt_total 25180
telemt_upstream_connect_success_total 24002
telemt_upstream_connect_fail_total 1178
telemt_upstream_connect_attempts_per_request{bucket="1"} 25180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1178
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4897
telemt_me_reconnect_success_total 2525
telemt_me_reader_eof_total 2608
telemt_me_idle_close_by_peer_total 2607
telemt_me_route_drop_no_conn_total 1482990
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1468979
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5799
telemt_desync_full_logged_total 1809
telemt_desync_suppressed_total 3990
telemt_desync_frames_bucket_total{bucket="1_2"} 1544
telemt_desync_frames_bucket_total{bucket="3_10"} 2134
telemt_desync_frames_bucket_total{bucket="gt_10"} 2121
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 2931
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2521
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 1488321
telemt_user_connections_current{user="hello"} 2910
telemt_user_octets_from_client{user="hello"} 26378527573 (24.57 GB)
telemt_user_octets_to_client{user="hello"} 322705662941 (300.54 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 951
telemt_user_unique_ips_recent_window{user="hello"} 423
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 73734.4 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5384981
telemt_connections_bad_total 989223
telemt_connections_current 3390
telemt_connections_me_current 3390
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 98615
telemt_upstream_connect_attempt_total 64759
telemt_upstream_connect_success_total 62267
telemt_upstream_connect_fail_total 2492
telemt_upstream_connect_attempts_per_request{bucket="1"} 64759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2492
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74814
telemt_me_reconnect_success_total 9406
telemt_me_reader_eof_total 9911
telemt_me_idle_close_by_peer_total 9908
telemt_me_route_drop_no_conn_total 2481336
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3736133
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16230
telemt_desync_full_logged_total 4964
telemt_desync_suppressed_total 11266
telemt_desync_frames_bucket_total{bucket="1_2"} 2667
telemt_desync_frames_bucket_total{bucket="3_10"} 6787
telemt_desync_frames_bucket_total{bucket="gt_10"} 6776
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 9647
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9382
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 3784244
telemt_user_connections_current{user="hello"} 3390
telemt_user_octets_from_client{user="hello"} 58941547499 (54.89 GB)
telemt_user_octets_to_client{user="hello"} 1388162685756 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1156
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 19977.1 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475731
telemt_connections_bad_total 31642
telemt_connections_current 914
telemt_connections_me_current 914
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 9787
telemt_upstream_connect_attempt_total 6961
telemt_upstream_connect_success_total 6764
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 6961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3864
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 547
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 410
telemt_me_reconnect_attempts_total 2777
telemt_me_reconnect_success_total 2723
telemt_me_reader_eof_total 2795
telemt_me_idle_close_by_peer_total 2794
telemt_me_route_drop_no_conn_total 331586
telemt_me_route_drop_channel_closed_total 119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375865
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1023
telemt_desync_full_logged_total 324
telemt_desync_suppressed_total 699
telemt_desync_frames_bucket_total{bucket="1_2"} 160
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 120
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2739
telemt_me_writer_restored_same_endpoint_total 2714
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 394560
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 4645667328 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 84218062282 (78.43 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 19975.5 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1323610
telemt_connections_bad_total 85249
telemt_connections_current 3006
telemt_connections_me_current 3006
telemt_handshake_timeouts_total 23588
telemt_upstream_connect_attempt_total 3331
telemt_upstream_connect_success_total 3304
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2273
telemt_me_reconnect_success_total 2247
telemt_me_reader_eof_total 2355
telemt_me_idle_close_by_peer_total 2355
telemt_me_route_drop_no_conn_total 514115
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1142293
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6149
telemt_desync_full_logged_total 1869
telemt_desync_suppressed_total 4280
telemt_desync_frames_bucket_total{bucket="1_2"} 1203
telemt_desync_frames_bucket_total{bucket="3_10"} 2134
telemt_desync_frames_bucket_total{bucket="gt_10"} 2812
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 2293
telemt_me_writer_restored_same_endpoint_total 2230
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1141587
telemt_user_connections_current{user="hello"} 3006
telemt_user_octets_from_client{user="hello"} 17713959512 (16.50 GB)
telemt_user_octets_to_client{user="hello"} 502610238096 (468.09 GB)
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 393
```