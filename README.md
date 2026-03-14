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

# Server Metrics 2026-03-14 17:14:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 14270.0 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80523
telemt_connections_bad_total 12384
telemt_handshake_timeouts_total 357
telemt_upstream_connect_attempt_total 3447
telemt_upstream_connect_success_total 3445
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 2718
telemt_me_reconnect_success_total 2689
telemt_me_reader_eof_total 2830
telemt_me_idle_close_by_peer_total 2830
telemt_me_route_drop_no_conn_total 29514
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65371
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 269
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2740
telemt_me_writer_restored_same_endpoint_total 2671
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 65301
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 1339074120 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 31512756180 (29.35 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 14268.2 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33848
telemt_connections_bad_total 406
telemt_handshake_timeouts_total 701
telemt_upstream_connect_attempt_total 4056
telemt_upstream_connect_success_total 4024
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 4056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 5839
telemt_me_reconnect_success_total 3267
telemt_me_reader_eof_total 3459
telemt_me_idle_close_by_peer_total 3459
telemt_me_route_drop_no_conn_total 17206
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31537
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3394
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3262
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 31519
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 387707964 (369.75 MB)
telemt_user_octets_to_client{user="hello"} 12481138348 (11.62 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 14272.5 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34411
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 1667
telemt_upstream_connect_attempt_total 5704
telemt_upstream_connect_success_total 5650
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 5704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 102431
telemt_me_reconnect_success_total 4578
telemt_me_reader_eof_total 4864
telemt_me_idle_close_by_peer_total 4864
telemt_me_route_drop_no_conn_total 12816
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30231
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4832
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 4540
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 30515
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2781797141 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 15854904794 (14.77 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 14277.5 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44526
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 279
telemt_upstream_connect_attempt_total 3765
telemt_upstream_connect_success_total 3748
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 3020
telemt_me_reconnect_success_total 3001
telemt_me_reader_eof_total 3121
telemt_me_idle_close_by_peer_total 3121
telemt_me_route_drop_no_conn_total 21248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42307
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 388
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3032
telemt_me_writer_restored_same_endpoint_total 2999
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 42186
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 488840572 (466.19 MB)
telemt_user_octets_to_client{user="hello"} 14101169784 (13.13 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 14270.6 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31654
telemt_connections_bad_total 2801
telemt_handshake_timeouts_total 1484
telemt_upstream_connect_attempt_total 3250
telemt_upstream_connect_success_total 3212
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 8978
telemt_me_reconnect_success_total 2456
telemt_me_reader_eof_total 2722
telemt_me_idle_close_by_peer_total 2722
telemt_me_route_drop_no_conn_total 11149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25964
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2679
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2452
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 25958
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 225519908 (215.07 MB)
telemt_user_octets_to_client{user="hello"} 7472462940 (6.96 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 14270.3 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116866
telemt_connections_bad_total 6946
telemt_handshake_timeouts_total 1309
telemt_upstream_connect_attempt_total 2926
telemt_upstream_connect_success_total 2870
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 2926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 7109
telemt_me_reconnect_success_total 2113
telemt_me_reader_eof_total 2316
telemt_me_idle_close_by_peer_total 2316
telemt_me_route_drop_no_conn_total 58342
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102913
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2288
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2109
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 102517
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 1911352020 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 52077736804 (48.50 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 72
```