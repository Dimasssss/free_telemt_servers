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

# Server Metrics 2026-03-18 02:02:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 112646.6 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1305930
telemt_connections_bad_total 9734
telemt_handshake_timeouts_total 32637
telemt_upstream_connect_attempt_total 25102
telemt_upstream_connect_success_total 24597
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 25101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33813
telemt_me_reconnect_success_total 16673
telemt_me_reader_eof_total 18101
telemt_me_idle_close_by_peer_total 18100
telemt_me_route_drop_no_conn_total 567143
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1202294
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7661
telemt_desync_full_logged_total 2264
telemt_desync_suppressed_total 5397
telemt_desync_frames_bucket_total{bucket="1_2"} 2053
telemt_desync_frames_bucket_total{bucket="3_10"} 2906
telemt_desync_frames_bucket_total{bucket="gt_10"} 2702
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17457
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16651
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 784
telemt_user_connections_total{user="hello"} 1196506
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 23037298551 (21.46 GB)
telemt_user_octets_to_client{user="hello"} 423386413819 (394.31 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 112897.9 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1379858
telemt_connections_bad_total 64215
telemt_handshake_timeouts_total 46904
telemt_upstream_connect_attempt_total 467847
telemt_upstream_connect_success_total 466273
telemt_upstream_connect_fail_total 1574
telemt_upstream_connect_attempts_per_request{bucket="1"} 467847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1574
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123158
telemt_me_reconnect_success_total 17718
telemt_me_reader_eof_total 19876
telemt_me_idle_close_by_peer_total 19863
telemt_me_route_drop_no_conn_total 355449
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 756450
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3518
telemt_desync_full_logged_total 1190
telemt_desync_suppressed_total 2328
telemt_desync_frames_bucket_total{bucket="1_2"} 688
telemt_desync_frames_bucket_total{bucket="3_10"} 1465
telemt_desync_frames_bucket_total{bucket="gt_10"} 1365
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 19283
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17700
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 1198801
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 16227794805 (15.11 GB)
telemt_user_octets_to_client{user="hello"} 420243710366 (391.38 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 112673.9 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826605
telemt_connections_bad_total 57267
telemt_handshake_timeouts_total 24433
telemt_upstream_connect_attempt_total 26376
telemt_upstream_connect_success_total 26224
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41238
telemt_me_reconnect_success_total 20547
telemt_me_reader_eof_total 22367
telemt_me_idle_close_by_peer_total 22360
telemt_me_route_drop_no_conn_total 329835
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699011
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2206
telemt_desync_full_logged_total 718
telemt_desync_suppressed_total 1488
telemt_desync_frames_bucket_total{bucket="1_2"} 625
telemt_desync_frames_bucket_total{bucket="3_10"} 857
telemt_desync_frames_bucket_total{bucket="gt_10"} 724
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 21470
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20535
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 923
telemt_user_connections_total{user="hello"} 697130
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 42616868720 (39.69 GB)
telemt_user_octets_to_client{user="hello"} 308657569048 (287.46 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 112733.4 (31h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1309987
telemt_connections_bad_total 57762
telemt_handshake_timeouts_total 22061
telemt_upstream_connect_attempt_total 89177
telemt_upstream_connect_success_total 86766
telemt_upstream_connect_fail_total 2411
telemt_upstream_connect_attempts_per_request{bucket="1"} 89177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2411
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36760
telemt_me_reconnect_success_total 16365
telemt_me_reader_eof_total 18037
telemt_me_idle_close_by_peer_total 18035
telemt_me_route_drop_no_conn_total 538925
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1064415
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3959
telemt_desync_full_logged_total 1312
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1662
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 17311
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16354
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 946
telemt_user_connections_total{user="hello"} 1127756
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 17665626654 (16.45 GB)
telemt_user_octets_to_client{user="hello"} 531057901830 (494.59 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 112705.3 (31h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 867038
telemt_connections_bad_total 100254
telemt_handshake_timeouts_total 6861
telemt_upstream_connect_attempt_total 45949
telemt_upstream_connect_success_total 45321
telemt_upstream_connect_fail_total 628
telemt_upstream_connect_attempts_per_request{bucket="1"} 45949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 413
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 628
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58164
telemt_me_reconnect_success_total 23202
telemt_me_reader_eof_total 25162
telemt_me_idle_close_by_peer_total 25159
telemt_me_route_drop_no_conn_total 276041
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700511
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3223
telemt_desync_full_logged_total 963
telemt_desync_suppressed_total 2260
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1287
telemt_desync_frames_bucket_total{bucket="gt_10"} 928
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24666
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23194
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1464
telemt_user_connections_total{user="hello"} 717114
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 13795685988 (12.85 GB)
telemt_user_octets_to_client{user="hello"} 355010749684 (330.63 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 112866.2 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1115295
telemt_connections_bad_total 117509
telemt_handshake_timeouts_total 9810
telemt_upstream_connect_attempt_total 22470
telemt_upstream_connect_success_total 22342
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28001
telemt_me_reconnect_success_total 16713
telemt_me_reader_eof_total 18128
telemt_me_idle_close_by_peer_total 18126
telemt_me_route_drop_no_conn_total 766745
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1089690
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
telemt_pool_swap_total 100
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17331
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16699
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 917305
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 14863732148 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 398292574352 (370.94 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 60633.5 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420050
telemt_connections_bad_total 44719
telemt_handshake_timeouts_total 11067
telemt_upstream_connect_attempt_total 22499
telemt_upstream_connect_success_total 22282
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 22499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30699
telemt_me_reconnect_success_total 19092
telemt_me_reader_eof_total 20184
telemt_me_idle_close_by_peer_total 20184
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 104058
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304455
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1322
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 912
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 587
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19668
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19056
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 576
telemt_user_connections_total{user="hello"} 304391
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 22543073165 (20.99 GB)
telemt_user_octets_to_client{user="hello"} 257927769902 (240.21 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 37
```