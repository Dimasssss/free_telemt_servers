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

# Server Metrics 2026-03-13 22:33:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 140404.8 (39h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578397
telemt_connections_bad_total 17749
telemt_handshake_timeouts_total 12805
telemt_upstream_connect_attempt_total 35605
telemt_upstream_connect_success_total 35427
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 35605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5126
telemt_me_reconnect_attempts_total 32708
telemt_me_reconnect_success_total 28047
telemt_me_reader_eof_total 29950
telemt_me_idle_close_by_peer_total 29949
telemt_me_route_drop_no_conn_total 190831
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497322
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
telemt_me_writer_removed_unexpected_total 28508
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28031
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 497216
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 15209373014 (14.16 GB)
telemt_user_octets_to_client{user="hello"} 245472191676 (228.61 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 140297.8 (38h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295573
telemt_connections_bad_total 2141
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 139534
telemt_upstream_connect_success_total 138509
telemt_upstream_connect_fail_total 1025
telemt_upstream_connect_attempts_per_request{bucket="1"} 139534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1025
telemt_me_keepalive_timeout_total 3710
telemt_me_reconnect_attempts_total 148899
telemt_me_reconnect_success_total 28203
telemt_me_reader_eof_total 32721
telemt_me_idle_close_by_peer_total 32721
telemt_me_route_drop_no_conn_total 88461
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177182
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
telemt_me_writer_removed_unexpected_total 32237
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 28186
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4034
telemt_user_connections_total{user="hello"} 280294
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 2960382155 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 86807075543 (80.85 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 140261.6 (38h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344300
telemt_connections_bad_total 2662
telemt_handshake_timeouts_total 28875
telemt_upstream_connect_attempt_total 37276
telemt_upstream_connect_success_total 37271
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 37276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2854
telemt_me_reconnect_attempts_total 31491
telemt_me_reconnect_success_total 30244
telemt_me_reader_eof_total 32455
telemt_me_idle_close_by_peer_total 32455
telemt_me_route_drop_no_conn_total 122259
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300736
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
telemt_me_writer_removed_unexpected_total 30588
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30224
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 300637
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 12360453932 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 124622694068 (116.06 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 140237.1 (38h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447789
telemt_connections_bad_total 15282
telemt_handshake_timeouts_total 4238
telemt_upstream_connect_attempt_total 64714
telemt_upstream_connect_success_total 54340
telemt_upstream_connect_fail_total 10374
telemt_upstream_connect_attempts_per_request{bucket="1"} 64714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10374
telemt_me_keepalive_timeout_total 4962
telemt_me_reconnect_attempts_total 130793
telemt_me_reconnect_success_total 28321
telemt_me_reader_eof_total 32311
telemt_me_idle_close_by_peer_total 32304
telemt_me_route_drop_no_conn_total 156350
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378247
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1639
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1159
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 623
telemt_desync_frames_bucket_total{bucket="gt_10"} 633
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 31878
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28311
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3557
telemt_user_connections_total{user="hello"} 397089
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 8991944895 (8.37 GB)
telemt_user_octets_to_client{user="hello"} 151603815996 (141.19 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 90408.7 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151287
telemt_connections_bad_total 22502
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 33644
telemt_upstream_connect_success_total 33333
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 33644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1315
telemt_me_reconnect_attempts_total 37322
telemt_me_reconnect_success_total 23923
telemt_me_reader_eof_total 25614
telemt_me_idle_close_by_peer_total 25614
telemt_me_route_drop_no_conn_total 46395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117630
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
telemt_me_writer_removed_unexpected_total 24567
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23905
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 644
telemt_user_connections_total{user="hello"} 122524
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 1420654933 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 57717052115 (53.75 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 140193.2 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 844064
telemt_connections_bad_total 27135
telemt_handshake_timeouts_total 25132
telemt_upstream_connect_attempt_total 28791
telemt_upstream_connect_success_total 28639
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 28791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 3245
telemt_me_reconnect_attempts_total 26349
telemt_me_reconnect_success_total 21696
telemt_me_reader_eof_total 23270
telemt_me_idle_close_by_peer_total 23267
telemt_me_route_drop_no_conn_total 402609
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790088
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
telemt_me_writer_removed_unexpected_total 22127
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21689
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 762942
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 13188531180 (12.28 GB)
telemt_user_octets_to_client{user="hello"} 383604858900 (357.26 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 31
```