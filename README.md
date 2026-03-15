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

# Server Metrics 2026-03-15 10:43:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 44924.4 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187821
telemt_connections_bad_total 1341
telemt_handshake_timeouts_total 4239
telemt_upstream_connect_attempt_total 11251
telemt_upstream_connect_success_total 11192
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 11251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 11332
telemt_me_reconnect_success_total 8959
telemt_me_reader_eof_total 9574
telemt_me_idle_close_by_peer_total 9574
telemt_me_route_drop_no_conn_total 413423
telemt_me_route_drop_channel_closed_total 61
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236123
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1407
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 562
telemt_desync_frames_bucket_total{bucket="gt_10"} 619
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9116
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 8928
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 175382
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 2851011112 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 180393346860 (168.00 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 44930.5 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60731
telemt_connections_bad_total 2309
telemt_handshake_timeouts_total 3054
telemt_upstream_connect_attempt_total 12074
telemt_upstream_connect_success_total 12074
telemt_upstream_connect_attempts_per_request{bucket="1"} 12074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12144
telemt_me_reconnect_success_total 9822
telemt_me_reader_eof_total 10539
telemt_me_idle_close_by_peer_total 10539
telemt_me_route_drop_no_conn_total 28515
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53432
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 10001
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9806
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 53432
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 1029335428 (981.65 MB)
telemt_user_octets_to_client{user="hello"} 22996468440 (21.42 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 44923.1 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68582
telemt_connections_bad_total 645
telemt_handshake_timeouts_total 2439
telemt_upstream_connect_attempt_total 12502
telemt_upstream_connect_success_total 12501
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 11451
telemt_me_reconnect_success_total 10251
telemt_me_reader_eof_total 11016
telemt_me_idle_close_by_peer_total 11016
telemt_me_route_drop_no_conn_total 25796
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62803
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10380
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10247
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 62727
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 9343270292 (8.70 GB)
telemt_user_octets_to_client{user="hello"} 38396049992 (35.76 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 44922.8 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89217
telemt_connections_bad_total 264
telemt_handshake_timeouts_total 592
telemt_upstream_connect_attempt_total 10652
telemt_upstream_connect_success_total 10651
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8465
telemt_me_reconnect_success_total 8424
telemt_me_reader_eof_total 8983
telemt_me_idle_close_by_peer_total 8983
telemt_me_route_drop_no_conn_total 36827
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81380
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8512
telemt_me_writer_restored_same_endpoint_total 8413
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 81310
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1603436440 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 49802572608 (46.38 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 19994.2 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33868
telemt_connections_bad_total 3735
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 6716
telemt_upstream_connect_success_total 6663
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 6716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 99873
telemt_me_reconnect_success_total 5463
telemt_me_reader_eof_total 5672
telemt_me_idle_close_by_peer_total 5672
telemt_me_route_drop_no_conn_total 11457
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28810
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5436
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5359
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 28950
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 439252757 (418.90 MB)
telemt_user_octets_to_client{user="hello"} 13025174335 (12.13 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 44922.1 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241564
telemt_connections_bad_total 44428
telemt_handshake_timeouts_total 1533
telemt_upstream_connect_attempt_total 9520
telemt_upstream_connect_success_total 9463
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 9520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 7272
telemt_me_reconnect_success_total 7229
telemt_me_reader_eof_total 7707
telemt_me_idle_close_by_peer_total 7707
telemt_me_route_drop_no_conn_total 106222
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189086
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7284
telemt_me_writer_restored_same_endpoint_total 7202
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 187455
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 4488194536 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 95112465468 (88.58 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 75
```