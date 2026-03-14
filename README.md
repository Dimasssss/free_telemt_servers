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

# Server Metrics 2026-03-14 09:50:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 181039.7 (50h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702097
telemt_connections_bad_total 32834
telemt_handshake_timeouts_total 13663
telemt_upstream_connect_attempt_total 45967
telemt_upstream_connect_success_total 45733
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 45967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5902
telemt_me_reconnect_attempts_total 41020
telemt_me_reconnect_success_total 36318
telemt_me_reader_eof_total 38827
telemt_me_idle_close_by_peer_total 38826
telemt_me_route_drop_no_conn_total 231872
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 600865
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2382
telemt_desync_full_logged_total 794
telemt_desync_suppressed_total 1588
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 999
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 36854
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36298
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 600743
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 17283558534 (16.10 GB)
telemt_user_octets_to_client{user="hello"} 287016866392 (267.31 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 180932.3 (50h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352904
telemt_connections_bad_total 2810
telemt_handshake_timeouts_total 3099
telemt_upstream_connect_attempt_total 153506
telemt_upstream_connect_success_total 152160
telemt_upstream_connect_fail_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 153506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1346
telemt_me_keepalive_timeout_total 5404
telemt_me_reconnect_attempts_total 186803
telemt_me_reconnect_success_total 39862
telemt_me_reader_eof_total 45506
telemt_me_idle_close_by_peer_total 45506
telemt_me_route_drop_no_conn_total 120361
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229956
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44833
telemt_me_refill_failed_total 4585
telemt_me_writer_restored_same_endpoint_total 39845
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4971
telemt_user_connections_total{user="hello"} 333060
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3428747211 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 106755681667 (99.42 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 180895.9 (50h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409296
telemt_connections_bad_total 3214
telemt_handshake_timeouts_total 35661
telemt_upstream_connect_attempt_total 47922
telemt_upstream_connect_success_total 47913
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3714
telemt_me_reconnect_attempts_total 40176
telemt_me_reconnect_success_total 38875
telemt_me_reader_eof_total 41783
telemt_me_idle_close_by_peer_total 41783
telemt_me_route_drop_no_conn_total 148597
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355991
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 39343
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38854
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 355718
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 13767623160 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 157156642140 (146.36 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 180871.5 (50h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517066
telemt_connections_bad_total 16708
telemt_handshake_timeouts_total 5200
telemt_upstream_connect_attempt_total 78359
telemt_upstream_connect_success_total 67699
telemt_upstream_connect_fail_total 10660
telemt_upstream_connect_attempts_per_request{bucket="1"} 78359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27748
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10660
telemt_me_keepalive_timeout_total 5557
telemt_me_reconnect_attempts_total 151967
telemt_me_reconnect_success_total 39674
telemt_me_reader_eof_total 44438
telemt_me_idle_close_by_peer_total 44430
telemt_me_route_drop_no_conn_total 187190
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442024
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1973
telemt_desync_full_logged_total 583
telemt_desync_suppressed_total 1390
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 43634
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 39664
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3960
telemt_user_connections_total{user="hello"} 460894
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 9897166071 (9.22 GB)
telemt_user_octets_to_client{user="hello"} 191174910800 (178.05 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 131043.0 (36h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217195
telemt_connections_bad_total 33443
telemt_handshake_timeouts_total 1960
telemt_upstream_connect_attempt_total 46268
telemt_upstream_connect_success_total 45817
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 46268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2679
telemt_me_reconnect_attempts_total 50281
telemt_me_reconnect_success_total 34405
telemt_me_reader_eof_total 36817
telemt_me_idle_close_by_peer_total 36817
telemt_me_route_drop_no_conn_total 65365
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171053
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 758
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 35212
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34387
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 807
telemt_user_connections_total{user="hello"} 175812
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 2643175061 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 82747152295 (77.06 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 180827.6 (50h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1045477
telemt_connections_bad_total 36929
telemt_handshake_timeouts_total 26800
telemt_upstream_connect_attempt_total 37719
telemt_upstream_connect_success_total 37519
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 37719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 4848
telemt_me_reconnect_attempts_total 33276
telemt_me_reconnect_success_total 28591
telemt_me_reader_eof_total 30658
telemt_me_idle_close_by_peer_total 30655
telemt_me_route_drop_no_conn_total 489587
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 968802
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 799
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 29097
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28584
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 941419
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 17441093212 (16.24 GB)
telemt_user_octets_to_client{user="hello"} 470891075804 (438.55 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 65
```