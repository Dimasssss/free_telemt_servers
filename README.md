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

# Server Metrics 2026-03-13 22:48:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 141320.4 (39h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580040
telemt_connections_bad_total 18136
telemt_handshake_timeouts_total 12823
telemt_upstream_connect_attempt_total 35852
telemt_upstream_connect_success_total 35672
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 35852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5129
telemt_me_reconnect_attempts_total 32907
telemt_me_reconnect_success_total 28245
telemt_me_reader_eof_total 30164
telemt_me_idle_close_by_peer_total 30163
telemt_me_route_drop_no_conn_total 191120
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498510
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
telemt_me_writer_removed_unexpected_total 28708
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28229
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 498404
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 15293126822 (14.24 GB)
telemt_user_octets_to_client{user="hello"} 247584417212 (230.58 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 141213.4 (39h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296525
telemt_connections_bad_total 2154
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 139784
telemt_upstream_connect_success_total 138755
telemt_upstream_connect_fail_total 1029
telemt_upstream_connect_attempts_per_request{bucket="1"} 139784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1029
telemt_me_keepalive_timeout_total 3716
telemt_me_reconnect_attempts_total 149102
telemt_me_reconnect_success_total 28404
telemt_me_reader_eof_total 32946
telemt_me_idle_close_by_peer_total 32946
telemt_me_route_drop_no_conn_total 89555
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178100
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
telemt_me_writer_removed_unexpected_total 32441
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 28387
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4037
telemt_user_connections_total{user="hello"} 281212
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 2965213959 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 87189482031 (81.20 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 141177.9 (39h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345557
telemt_connections_bad_total 2686
telemt_handshake_timeouts_total 29437
telemt_upstream_connect_attempt_total 37519
telemt_upstream_connect_success_total 37514
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 37519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2869
telemt_me_reconnect_attempts_total 31691
telemt_me_reconnect_success_total 30443
telemt_me_reader_eof_total 32668
telemt_me_idle_close_by_peer_total 32668
telemt_me_route_drop_no_conn_total 122538
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301382
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
telemt_me_writer_removed_unexpected_total 30789
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30423
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 301283
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 12364620128 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 124843512452 (116.27 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 141152.6 (39h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448581
telemt_connections_bad_total 15284
telemt_handshake_timeouts_total 4239
telemt_upstream_connect_attempt_total 64964
telemt_upstream_connect_success_total 54589
telemt_upstream_connect_fail_total 10375
telemt_upstream_connect_attempts_per_request{bucket="1"} 64964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 311
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10375
telemt_me_keepalive_timeout_total 4971
telemt_me_reconnect_attempts_total 130999
telemt_me_reconnect_success_total 28526
telemt_me_reader_eof_total 32539
telemt_me_idle_close_by_peer_total 32532
telemt_me_route_drop_no_conn_total 156698
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379011
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
telemt_me_writer_removed_unexpected_total 32085
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28516
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3559
telemt_user_connections_total{user="hello"} 397853
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 8996951907 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 151683470272 (141.27 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 91324.2 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152876
telemt_connections_bad_total 22673
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 33886
telemt_upstream_connect_success_total 33572
telemt_upstream_connect_fail_total 314
telemt_upstream_connect_attempts_per_request{bucket="1"} 33886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 314
telemt_me_keepalive_timeout_total 1316
telemt_me_reconnect_attempts_total 37518
telemt_me_reconnect_success_total 24118
telemt_me_reader_eof_total 25822
telemt_me_idle_close_by_peer_total 25822
telemt_me_route_drop_no_conn_total 46592
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119052
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
telemt_me_writer_removed_unexpected_total 24765
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 24100
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 647
telemt_user_connections_total{user="hello"} 123935
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 1460467557 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 58243761119 (54.24 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 141108.6 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 846654
telemt_connections_bad_total 27138
telemt_handshake_timeouts_total 25135
telemt_upstream_connect_attempt_total 28970
telemt_upstream_connect_success_total 28818
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 28970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 3317
telemt_me_reconnect_attempts_total 26485
telemt_me_reconnect_success_total 21829
telemt_me_reader_eof_total 23414
telemt_me_idle_close_by_peer_total 23411
telemt_me_route_drop_no_conn_total 404024
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792607
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
telemt_me_writer_removed_unexpected_total 22262
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21822
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 765461
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 13211490528 (12.30 GB)
telemt_user_octets_to_client{user="hello"} 387255780364 (360.66 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 34
```