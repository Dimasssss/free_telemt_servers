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

# Server Metrics 2026-03-13 16:06:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 117184.7 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487099
telemt_connections_bad_total 3556
telemt_handshake_timeouts_total 8888
telemt_upstream_connect_attempt_total 29230
telemt_upstream_connect_success_total 29088
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 29230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2508
telemt_me_reconnect_attempts_total 26748
telemt_me_reconnect_success_total 23211
telemt_me_reader_eof_total 24799
telemt_me_idle_close_by_peer_total 24798
telemt_me_route_drop_no_conn_total 159495
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427880
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1387
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 901
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 23566
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23195
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 427452
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 7595711876 (7.07 GB)
telemt_user_octets_to_client{user="hello"} 199855073280 (186.13 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 117077.5 (32h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235895
telemt_connections_bad_total 1883
telemt_handshake_timeouts_total 1695
telemt_upstream_connect_attempt_total 92459
telemt_upstream_connect_success_total 91666
telemt_upstream_connect_fail_total 792
telemt_upstream_connect_attempts_per_request{bucket="1"} 92458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 792
telemt_me_keepalive_timeout_total 1417
telemt_me_reconnect_attempts_total 116309
telemt_me_reconnect_success_total 26024
telemt_me_reader_eof_total 29602
telemt_me_idle_close_by_peer_total 29602
telemt_me_route_drop_no_conn_total 81733
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 28
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29069
telemt_me_refill_failed_total 2817
telemt_me_writer_restored_same_endpoint_total 26007
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3045
telemt_user_connections_total{user="hello"} 223190
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 2313508807 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 69698124127 (64.91 GB)
telemt_user_msgs_from_client{user="hello"} 919786
telemt_user_msgs_to_client{user="hello"} 5560188
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 117041.2 (32h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283135
telemt_connections_bad_total 2441
telemt_handshake_timeouts_total 13764
telemt_upstream_connect_attempt_total 31289
telemt_upstream_connect_success_total 31285
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16744
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2414
telemt_me_reconnect_attempts_total 26621
telemt_me_reconnect_success_total 25400
telemt_me_reader_eof_total 27227
telemt_me_idle_close_by_peer_total 27227
telemt_me_route_drop_no_conn_total 102211
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256886
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 25684
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25380
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 256800
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 9683428268 (9.02 GB)
telemt_user_octets_to_client{user="hello"} 108452391684 (101.00 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 117016.7 (32h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384235
telemt_connections_bad_total 15063
telemt_handshake_timeouts_total 3787
telemt_upstream_connect_attempt_total 43165
telemt_upstream_connect_success_total 32983
telemt_upstream_connect_fail_total 10182
telemt_upstream_connect_attempts_per_request{bucket="1"} 43165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10182
telemt_me_keepalive_timeout_total 4174
telemt_me_reconnect_attempts_total 105557
telemt_me_reconnect_success_total 24108
telemt_me_reader_eof_total 27361
telemt_me_idle_close_by_peer_total 27354
telemt_me_route_drop_no_conn_total 137680
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333594
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1346
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 947
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 516
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26960
telemt_me_refill_failed_total 2540
telemt_me_writer_restored_same_endpoint_total 24098
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2852
telemt_user_connections_total{user="hello"} 336505
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 6967114954 (6.49 GB)
telemt_user_octets_to_client{user="hello"} 124734630493 (116.17 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 67188.1 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106032
telemt_connections_bad_total 13738
telemt_handshake_timeouts_total 1326
telemt_upstream_connect_attempt_total 27078
telemt_upstream_connect_success_total 26841
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 27078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 1058
telemt_me_reconnect_attempts_total 29750
telemt_me_reconnect_success_total 18577
telemt_me_reader_eof_total 19910
telemt_me_idle_close_by_peer_total 19910
telemt_me_route_drop_no_conn_total 32512
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82637
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 19083
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18559
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 87536
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 1009828705 (963.05 MB)
telemt_user_octets_to_client{user="hello"} 26800957739 (24.96 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 116974.2 (32h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710279
telemt_connections_bad_total 24632
telemt_handshake_timeouts_total 23688
telemt_upstream_connect_attempt_total 24456
telemt_upstream_connect_success_total 24334
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 24456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 2558
telemt_me_reconnect_attempts_total 23168
telemt_me_reconnect_success_total 18539
telemt_me_reader_eof_total 19892
telemt_me_idle_close_by_peer_total 19889
telemt_me_route_drop_no_conn_total 335333
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665745
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 666
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 18919
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18532
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 638649
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 11160397108 (10.39 GB)
telemt_user_octets_to_client{user="hello"} 328266352268 (305.72 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 65
```