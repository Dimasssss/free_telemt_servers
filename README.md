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

# Server Metrics 2026-03-13 22:43:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 141014.5 (39h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 579607
telemt_connections_bad_total 18035
telemt_handshake_timeouts_total 12822
telemt_upstream_connect_attempt_total 35799
telemt_upstream_connect_success_total 35619
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 35799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5128
telemt_me_reconnect_attempts_total 32855
telemt_me_reconnect_success_total 28193
telemt_me_reader_eof_total 30111
telemt_me_idle_close_by_peer_total 30110
telemt_me_route_drop_no_conn_total 190992
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498192
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1592
telemt_desync_full_logged_total 539
telemt_desync_suppressed_total 1053
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 28655
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28177
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 498086
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 15287984698 (14.24 GB)
telemt_user_octets_to_client{user="hello"} 247080761384 (230.11 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 140908.5 (39h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296240
telemt_connections_bad_total 2153
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 139739
telemt_upstream_connect_success_total 138710
telemt_upstream_connect_fail_total 1029
telemt_upstream_connect_attempts_per_request{bucket="1"} 139739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1029
telemt_me_keepalive_timeout_total 3713
telemt_me_reconnect_attempts_total 149057
telemt_me_reconnect_success_total 28360
telemt_me_reader_eof_total 32899
telemt_me_idle_close_by_peer_total 32899
telemt_me_route_drop_no_conn_total 89452
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177822
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
telemt_me_writer_removed_unexpected_total 32394
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 28343
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4034
telemt_user_connections_total{user="hello"} 280934
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 2963151447 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 86848830911 (80.88 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 140872.7 (39h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345173
telemt_connections_bad_total 2686
telemt_handshake_timeouts_total 29249
telemt_upstream_connect_attempt_total 37457
telemt_upstream_connect_success_total 37452
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 37457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2862
telemt_me_reconnect_attempts_total 31629
telemt_me_reconnect_success_total 30382
telemt_me_reader_eof_total 32605
telemt_me_idle_close_by_peer_total 32605
telemt_me_route_drop_no_conn_total 122440
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301200
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
telemt_me_writer_removed_unexpected_total 30726
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30362
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 301101
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 12363668332 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 124822697260 (116.25 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 140847.7 (39h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448364
telemt_connections_bad_total 15284
telemt_handshake_timeouts_total 4239
telemt_upstream_connect_attempt_total 64917
telemt_upstream_connect_success_total 54542
telemt_upstream_connect_fail_total 10375
telemt_upstream_connect_attempts_per_request{bucket="1"} 64917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10375
telemt_me_keepalive_timeout_total 4963
telemt_me_reconnect_attempts_total 130952
telemt_me_reconnect_success_total 28479
telemt_me_reader_eof_total 32492
telemt_me_idle_close_by_peer_total 32485
telemt_me_route_drop_no_conn_total 156617
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378806
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
telemt_me_writer_removed_unexpected_total 32037
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28469
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3558
telemt_user_connections_total{user="hello"} 397648
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 8995708335 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 151636432840 (141.22 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 91019.3 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152228
telemt_connections_bad_total 22618
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 33790
telemt_upstream_connect_success_total 33475
telemt_upstream_connect_fail_total 314
telemt_upstream_connect_attempts_per_request{bucket="1"} 33789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 314
telemt_me_keepalive_timeout_total 1316
telemt_me_reconnect_attempts_total 37422
telemt_me_reconnect_success_total 24022
telemt_me_reader_eof_total 25717
telemt_me_idle_close_by_peer_total 25717
telemt_me_route_drop_no_conn_total 46531
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118457
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
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 24669
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 24004
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 647
telemt_user_connections_total{user="hello"} 123343
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 1447293693 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 58227832511 (54.23 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 140803.8 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845903
telemt_connections_bad_total 27137
telemt_handshake_timeouts_total 25133
telemt_upstream_connect_attempt_total 28934
telemt_upstream_connect_success_total 28782
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 28934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 3251
telemt_me_reconnect_attempts_total 26449
telemt_me_reconnect_success_total 21793
telemt_me_reader_eof_total 23377
telemt_me_idle_close_by_peer_total 23374
telemt_me_route_drop_no_conn_total 403645
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791895
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
telemt_me_writer_removed_unexpected_total 22226
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21786
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 764749
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 13205229464 (12.30 GB)
telemt_user_octets_to_client{user="hello"} 386148811160 (359.63 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 26
```