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

# Server Metrics 2026-03-18 02:28:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 114174.0 (31h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1319410
telemt_connections_bad_total 10146
telemt_handshake_timeouts_total 33155
telemt_upstream_connect_attempt_total 25364
telemt_upstream_connect_success_total 24860
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 25364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34032
telemt_me_reconnect_success_total 16892
telemt_me_reader_eof_total 18335
telemt_me_idle_close_by_peer_total 18334
telemt_me_route_drop_no_conn_total 570347
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1214389
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7746
telemt_desync_full_logged_total 2293
telemt_desync_suppressed_total 5453
telemt_desync_frames_bucket_total{bucket="1_2"} 2068
telemt_desync_frames_bucket_total{bucket="3_10"} 2955
telemt_desync_frames_bucket_total{bucket="gt_10"} 2723
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17679
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16870
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 787
telemt_user_connections_total{user="hello"} 1208601
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 24482538379 (22.80 GB)
telemt_user_octets_to_client{user="hello"} 426276789603 (397.00 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 114425.3 (31h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1391589
telemt_connections_bad_total 64218
telemt_handshake_timeouts_total 47137
telemt_upstream_connect_attempt_total 468227
telemt_upstream_connect_success_total 466646
telemt_upstream_connect_fail_total 1581
telemt_upstream_connect_attempts_per_request{bucket="1"} 468227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1581
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123444
telemt_me_reconnect_success_total 18004
telemt_me_reader_eof_total 20176
telemt_me_idle_close_by_peer_total 20163
telemt_me_route_drop_no_conn_total 358639
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767553
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3601
telemt_desync_full_logged_total 1229
telemt_desync_suppressed_total 2372
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 1500
telemt_desync_frames_bucket_total{bucket="gt_10"} 1391
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19569
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17986
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 1209904
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 16337245849 (15.22 GB)
telemt_user_octets_to_client{user="hello"} 424481673434 (395.33 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 114201.5 (31h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 841319
telemt_connections_bad_total 58538
telemt_handshake_timeouts_total 24591
telemt_upstream_connect_attempt_total 26659
telemt_upstream_connect_success_total 26507
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41478
telemt_me_reconnect_success_total 20786
telemt_me_reader_eof_total 22614
telemt_me_idle_close_by_peer_total 22607
telemt_me_route_drop_no_conn_total 332158
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707547
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2225
telemt_desync_full_logged_total 721
telemt_desync_suppressed_total 1504
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 728
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 21710
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20774
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 924
telemt_user_connections_total{user="hello"} 705665
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 43984604064 (40.96 GB)
telemt_user_octets_to_client{user="hello"} 314220794880 (292.64 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 114260.8 (31h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1319228
telemt_connections_bad_total 59376
telemt_handshake_timeouts_total 22106
telemt_upstream_connect_attempt_total 89411
telemt_upstream_connect_success_total 86998
telemt_upstream_connect_fail_total 2413
telemt_upstream_connect_attempts_per_request{bucket="1"} 89411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2413
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36950
telemt_me_reconnect_success_total 16554
telemt_me_reader_eof_total 18237
telemt_me_idle_close_by_peer_total 18235
telemt_me_route_drop_no_conn_total 542076
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1071719
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3982
telemt_desync_full_logged_total 1318
telemt_desync_suppressed_total 2664
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1671
telemt_desync_frames_bucket_total{bucket="gt_10"} 1339
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 17505
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16543
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 951
telemt_user_connections_total{user="hello"} 1135093
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 17800988090 (16.58 GB)
telemt_user_octets_to_client{user="hello"} 537787417898 (500.85 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 114232.7 (31h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 877048
telemt_connections_bad_total 100854
telemt_handshake_timeouts_total 6876
telemt_upstream_connect_attempt_total 46208
telemt_upstream_connect_success_total 45579
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 46208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58379
telemt_me_reconnect_success_total 23417
telemt_me_reader_eof_total 25384
telemt_me_idle_close_by_peer_total 25381
telemt_me_route_drop_no_conn_total 280231
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709639
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3231
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 2262
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1289
telemt_desync_frames_bucket_total{bucket="gt_10"} 934
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24883
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23409
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1466
telemt_user_connections_total{user="hello"} 726198
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 13936354704 (12.98 GB)
telemt_user_octets_to_client{user="hello"} 358697764564 (334.06 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 114393.7 (31h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1126493
telemt_connections_bad_total 121595
telemt_handshake_timeouts_total 9889
telemt_upstream_connect_attempt_total 22778
telemt_upstream_connect_success_total 22648
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28221
telemt_me_reconnect_success_total 16932
telemt_me_reader_eof_total 18363
telemt_me_idle_close_by_peer_total 18361
telemt_me_route_drop_no_conn_total 776146
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1100761
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 102
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17554
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16918
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 924015
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 14934186628 (13.91 GB)
telemt_user_octets_to_client{user="hello"} 403616750368 (375.90 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 62160.9 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429075
telemt_connections_bad_total 44738
telemt_handshake_timeouts_total 11377
telemt_upstream_connect_attempt_total 22909
telemt_upstream_connect_success_total 22687
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 22909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31044
telemt_me_reconnect_success_total 19437
telemt_me_reader_eof_total 20544
telemt_me_idle_close_by_peer_total 20544
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 105854
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311020
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1362
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 930
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 614
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20015
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19399
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 578
telemt_user_connections_total{user="hello"} 310956
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 22617440289 (21.06 GB)
telemt_user_octets_to_client{user="hello"} 260246075458 (242.37 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 35
```