# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-18 06:37:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 129140.3 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1626483
telemt_connections_bad_total 11543
telemt_handshake_timeouts_total 36543
telemt_upstream_connect_attempt_total 28025
telemt_upstream_connect_success_total 27504
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 28025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 35941
telemt_me_reconnect_success_total 18786
telemt_me_reader_eof_total 20355
telemt_me_idle_close_by_peer_total 20354
telemt_me_route_drop_no_conn_total 633772
telemt_me_route_drop_channel_closed_total 178
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1384741
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8405
telemt_desync_full_logged_total 2536
telemt_desync_suppressed_total 5869
telemt_desync_frames_bucket_total{bucket="1_2"} 2192
telemt_desync_frames_bucket_total{bucket="3_10"} 3236
telemt_desync_frames_bucket_total{bucket="gt_10"} 2977
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19602
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18764
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 816
telemt_user_connections_total{user="hello"} 1378990
telemt_user_connections_current{user="hello"} 1102
telemt_user_octets_from_client{user="hello"} 32511083427 (30.28 GB)
telemt_user_octets_to_client{user="hello"} 494406956879 (460.45 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 129391.5 (35h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1730222
telemt_connections_bad_total 85706
telemt_handshake_timeouts_total 55527
telemt_upstream_connect_attempt_total 471459
telemt_upstream_connect_success_total 469821
telemt_upstream_connect_fail_total 1638
telemt_upstream_connect_attempts_per_request{bucket="1"} 471459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1638
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 127207
telemt_me_reconnect_success_total 20474
telemt_me_reader_eof_total 22787
telemt_me_idle_close_by_peer_total 22774
telemt_me_route_drop_no_conn_total 462501
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1065271
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4908
telemt_desync_full_logged_total 1712
telemt_desync_suppressed_total 3196
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1986
telemt_desync_frames_bucket_total{bucket="gt_10"} 1979
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22108
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20456
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1634
telemt_user_connections_total{user="hello"} 1507557
telemt_user_connections_current{user="hello"} 2336
telemt_user_octets_from_client{user="hello"} 22577823569 (21.03 GB)
telemt_user_octets_to_client{user="hello"} 589062016614 (548.61 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 702
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 129167.6 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1226752
telemt_connections_bad_total 80949
telemt_handshake_timeouts_total 31182
telemt_upstream_connect_attempt_total 29251
telemt_upstream_connect_success_total 29086
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 29251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 43322
telemt_me_reconnect_success_total 22614
telemt_me_reader_eof_total 24574
telemt_me_idle_close_by_peer_total 24567
telemt_me_route_drop_no_conn_total 411660
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 923597
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3171
telemt_desync_full_logged_total 1026
telemt_desync_suppressed_total 2145
telemt_desync_frames_bucket_total{bucket="1_2"} 837
telemt_desync_frames_bucket_total{bucket="3_10"} 1226
telemt_desync_frames_bucket_total{bucket="gt_10"} 1108
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23570
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22602
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 956
telemt_user_connections_total{user="hello"} 921672
telemt_user_connections_current{user="hello"} 1633
telemt_user_octets_from_client{user="hello"} 47540249144 (44.28 GB)
telemt_user_octets_to_client{user="hello"} 451017715020 (420.04 GB)
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 129226.7 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1623440
telemt_connections_bad_total 83415
telemt_handshake_timeouts_total 28622
telemt_upstream_connect_attempt_total 92332
telemt_upstream_connect_success_total 89879
telemt_upstream_connect_fail_total 2453
telemt_upstream_connect_attempts_per_request{bucket="1"} 92332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2453
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 39109
telemt_me_reconnect_success_total 18686
telemt_me_reader_eof_total 20486
telemt_me_idle_close_by_peer_total 20483
telemt_me_route_drop_no_conn_total 648056
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1329995
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5187
telemt_desync_full_logged_total 1667
telemt_desync_suppressed_total 3520
telemt_desync_frames_bucket_total{bucket="1_2"} 1228
telemt_desync_frames_bucket_total{bucket="3_10"} 2139
telemt_desync_frames_bucket_total{bucket="gt_10"} 1820
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19669
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18666
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 983
telemt_user_connections_total{user="hello"} 1393246
telemt_user_connections_current{user="hello"} 2142
telemt_user_octets_from_client{user="hello"} 23463688550 (21.85 GB)
telemt_user_octets_to_client{user="hello"} 673668676866 (627.40 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 129198.4 (35h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1161534
telemt_connections_bad_total 106933
telemt_handshake_timeouts_total 12311
telemt_upstream_connect_attempt_total 49404
telemt_upstream_connect_success_total 48723
telemt_upstream_connect_fail_total 681
telemt_upstream_connect_attempts_per_request{bucket="1"} 49404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 681
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60789
telemt_me_reconnect_success_total 25817
telemt_me_reader_eof_total 27898
telemt_me_idle_close_by_peer_total 27895
telemt_me_route_drop_no_conn_total 374702
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4129
telemt_desync_full_logged_total 1269
telemt_desync_suppressed_total 2860
telemt_desync_frames_bucket_total{bucket="1_2"} 1137
telemt_desync_frames_bucket_total{bucket="3_10"} 1590
telemt_desync_frames_bucket_total{bucket="gt_10"} 1402
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27307
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25809
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1490
telemt_user_connections_total{user="hello"} 973142
telemt_user_connections_current{user="hello"} 1731
telemt_user_octets_from_client{user="hello"} 17997580228 (16.76 GB)
telemt_user_octets_to_client{user="hello"} 491710154244 (457.94 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 270
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 129359.8 (35h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254426
telemt_connections_bad_total 132346
telemt_handshake_timeouts_total 10763
telemt_upstream_connect_attempt_total 25625
telemt_upstream_connect_success_total 25472
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 25625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 30356
telemt_me_reconnect_success_total 19058
telemt_me_reader_eof_total 20644
telemt_me_idle_close_by_peer_total 20642
telemt_me_route_drop_no_conn_total 841594
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1226378
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2376
telemt_desync_full_logged_total 838
telemt_desync_suppressed_total 1538
telemt_desync_frames_bucket_total{bucket="1_2"} 531
telemt_desync_frames_bucket_total{bucket="3_10"} 910
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19703
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19044
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 645
telemt_user_connections_total{user="hello"} 1035039
telemt_user_connections_current{user="hello"} 877
telemt_user_octets_from_client{user="hello"} 16332110536 (15.21 GB)
telemt_user_octets_to_client{user="hello"} 459424142368 (427.87 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 77126.7 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642168
telemt_connections_bad_total 57832
telemt_handshake_timeouts_total 14398
telemt_upstream_connect_attempt_total 26219
telemt_upstream_connect_success_total 25944
telemt_upstream_connect_fail_total 275
telemt_upstream_connect_attempts_per_request{bucket="1"} 26219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 275
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 33586
telemt_me_reconnect_success_total 21969
telemt_me_reader_eof_total 23217
telemt_me_idle_close_by_peer_total 23217
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 165917
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477112
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2087
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 1374
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 920
telemt_desync_frames_bucket_total{bucket="gt_10"} 824
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22566
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21924
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 476859
telemt_user_connections_current{user="hello"} 1324
telemt_user_octets_from_client{user="hello"} 27467486729 (25.58 GB)
telemt_user_octets_to_client{user="hello"} 365468667782 (340.37 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 158
```