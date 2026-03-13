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

# Server Metrics 2026-03-13 22:38:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 140709.1 (39h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578951
telemt_connections_bad_total 17891
telemt_handshake_timeouts_total 12821
telemt_upstream_connect_attempt_total 35724
telemt_upstream_connect_success_total 35544
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 35724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5126
telemt_me_reconnect_attempts_total 32780
telemt_me_reconnect_success_total 28119
telemt_me_reader_eof_total 30036
telemt_me_idle_close_by_peer_total 30035
telemt_me_route_drop_no_conn_total 190912
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497697
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1590
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1052
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 28580
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28103
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 497591
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 15214857286 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 246070294304 (229.17 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 140603.0 (39h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295927
telemt_connections_bad_total 2153
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 139663
telemt_upstream_connect_success_total 138634
telemt_upstream_connect_fail_total 1029
telemt_upstream_connect_attempts_per_request{bucket="1"} 139663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1029
telemt_me_keepalive_timeout_total 3712
telemt_me_reconnect_attempts_total 148981
telemt_me_reconnect_success_total 28284
telemt_me_reader_eof_total 32823
telemt_me_idle_close_by_peer_total 32823
telemt_me_route_drop_no_conn_total 89004
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177510
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 32318
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 28267
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4034
telemt_user_connections_total{user="hello"} 280622
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 2961738663 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 86831277763 (80.87 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 140567.8 (39h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344734
telemt_connections_bad_total 2686
telemt_handshake_timeouts_total 29064
telemt_upstream_connect_attempt_total 37378
telemt_upstream_connect_success_total 37373
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 37378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2855
telemt_me_reconnect_attempts_total 31550
telemt_me_reconnect_success_total 30303
telemt_me_reader_eof_total 32526
telemt_me_idle_close_by_peer_total 32526
telemt_me_route_drop_no_conn_total 122356
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300954
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 30647
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30283
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 300855
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 12362044948 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 124682803780 (116.12 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 140542.3 (39h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448100
telemt_connections_bad_total 15284
telemt_handshake_timeouts_total 4239
telemt_upstream_connect_attempt_total 64835
telemt_upstream_connect_success_total 54460
telemt_upstream_connect_fail_total 10375
telemt_upstream_connect_attempts_per_request{bucket="1"} 64835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 308
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10375
telemt_me_keepalive_timeout_total 4963
telemt_me_reconnect_attempts_total 130870
telemt_me_reconnect_success_total 28397
telemt_me_reader_eof_total 32403
telemt_me_idle_close_by_peer_total 32396
telemt_me_route_drop_no_conn_total 156450
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378548
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1641
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 1159
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 633
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 31955
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28387
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3558
telemt_user_connections_total{user="hello"} 397390
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 8993081591 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 151610507676 (141.20 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 90713.8 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151618
telemt_connections_bad_total 22559
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 33704
telemt_upstream_connect_success_total 33393
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 33704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1315
telemt_me_reconnect_attempts_total 37382
telemt_me_reconnect_success_total 23983
telemt_me_reader_eof_total 25676
telemt_me_idle_close_by_peer_total 25676
telemt_me_route_drop_no_conn_total 46452
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117901
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 24629
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23965
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 646
telemt_user_connections_total{user="hello"} 122793
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 1432358801 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 58070629247 (54.08 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 140498.2 (39h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845036
telemt_connections_bad_total 27135
telemt_handshake_timeouts_total 25132
telemt_upstream_connect_attempt_total 28861
telemt_upstream_connect_success_total 28709
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 28861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 3251
telemt_me_reconnect_attempts_total 26376
telemt_me_reconnect_success_total 21723
telemt_me_reader_eof_total 23298
telemt_me_idle_close_by_peer_total 23295
telemt_me_route_drop_no_conn_total 402992
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791042
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 22154
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21716
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 763896
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 13197647684 (12.29 GB)
telemt_user_octets_to_client{user="hello"} 385036662860 (358.59 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 30
```