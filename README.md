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

# Server Metrics 2026-03-13 22:28:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 140099.8 (38h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577880
telemt_connections_bad_total 17567
telemt_handshake_timeouts_total 12805
telemt_upstream_connect_attempt_total 35562
telemt_upstream_connect_success_total 35384
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 35562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5124
telemt_me_reconnect_attempts_total 32665
telemt_me_reconnect_success_total 28004
telemt_me_reader_eof_total 29908
telemt_me_idle_close_by_peer_total 29907
telemt_me_route_drop_no_conn_total 190665
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496998
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 28465
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27988
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 496892
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 15205750250 (14.16 GB)
telemt_user_octets_to_client{user="hello"} 245389621024 (228.54 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 139992.3 (38h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295297
telemt_connections_bad_total 2141
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 139456
telemt_upstream_connect_success_total 138431
telemt_upstream_connect_fail_total 1025
telemt_upstream_connect_attempts_per_request{bucket="1"} 139456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1025
telemt_me_keepalive_timeout_total 3710
telemt_me_reconnect_attempts_total 148821
telemt_me_reconnect_success_total 28124
telemt_me_reader_eof_total 32643
telemt_me_idle_close_by_peer_total 32643
telemt_me_route_drop_no_conn_total 88226
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176911
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 32159
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 28107
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4035
telemt_user_connections_total{user="hello"} 280024
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 2958910015 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 86712304287 (80.76 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 139956.2 (38h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343755
telemt_connections_bad_total 2662
telemt_handshake_timeouts_total 28683
telemt_upstream_connect_attempt_total 37226
telemt_upstream_connect_success_total 37221
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 37226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2852
telemt_me_reconnect_attempts_total 31443
telemt_me_reconnect_success_total 30196
telemt_me_reader_eof_total 32407
telemt_me_idle_close_by_peer_total 32407
telemt_me_route_drop_no_conn_total 122067
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300396
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
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 30540
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30176
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 300297
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 12357545516 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 124270258188 (115.74 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 139931.6 (38h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447449
telemt_connections_bad_total 15282
telemt_handshake_timeouts_total 4237
telemt_upstream_connect_attempt_total 64625
telemt_upstream_connect_success_total 54251
telemt_upstream_connect_fail_total 10374
telemt_upstream_connect_attempts_per_request{bucket="1"} 64625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 306
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10374
telemt_me_keepalive_timeout_total 4957
telemt_me_reconnect_attempts_total 130704
telemt_me_reconnect_success_total 28233
telemt_me_reader_eof_total 32221
telemt_me_idle_close_by_peer_total 32214
telemt_me_route_drop_no_conn_total 156209
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377921
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1620
telemt_desync_full_logged_total 475
telemt_desync_suppressed_total 1145
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 621
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 31788
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28223
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3555
telemt_user_connections_total{user="hello"} 396763
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 8990119035 (8.37 GB)
telemt_user_octets_to_client{user="hello"} 151455516840 (141.05 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 90103.2 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151001
telemt_connections_bad_total 22445
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 33542
telemt_upstream_connect_success_total 33231
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 33542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1313
telemt_me_reconnect_attempts_total 37222
telemt_me_reconnect_success_total 23823
telemt_me_reader_eof_total 25492
telemt_me_idle_close_by_peer_total 25492
telemt_me_route_drop_no_conn_total 46346
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117418
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
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 24467
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23805
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 644
telemt_user_connections_total{user="hello"} 122312
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 1420262297 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 57694083351 (53.73 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 139887.6 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842938
telemt_connections_bad_total 27134
telemt_handshake_timeouts_total 25128
telemt_upstream_connect_attempt_total 28758
telemt_upstream_connect_success_total 28606
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 28758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 3245
telemt_me_reconnect_attempts_total 26316
telemt_me_reconnect_success_total 21663
telemt_me_reader_eof_total 23237
telemt_me_idle_close_by_peer_total 23234
telemt_me_route_drop_no_conn_total 401991
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788998
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 22094
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21656
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 761852
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 13177420680 (12.27 GB)
telemt_user_octets_to_client{user="hello"} 381611638980 (355.40 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 32
```