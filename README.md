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

# Server Metrics 2026-03-12 17:40:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 36398.3 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189389
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 4936
telemt_upstream_connect_attempt_total 9292
telemt_upstream_connect_success_total 9256
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 9292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 625
telemt_me_reconnect_attempts_total 10819
telemt_me_reconnect_success_total 7373
telemt_me_reader_eof_total 7813
telemt_me_idle_close_by_peer_total 7812
telemt_me_route_drop_no_conn_total 55251
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160565
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 628
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 393
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7561
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 7357
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 160526
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 2886476808 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 68258610164 (63.57 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 36291.3 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79894
telemt_connections_bad_total 468
telemt_handshake_timeouts_total 653
telemt_upstream_connect_attempt_total 11558
telemt_upstream_connect_success_total 11314
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 11558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 37376
telemt_me_reconnect_success_total 8958
telemt_me_reader_eof_total 10019
telemt_me_idle_close_by_peer_total 10019
telemt_me_route_drop_no_conn_total 34987
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75399
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9918
telemt_me_refill_failed_total 887
telemt_me_writer_restored_same_endpoint_total 8943
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 960
telemt_user_connections_total{user="hello"} 75888
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 828101321 (789.74 MB)
telemt_user_octets_to_client{user="hello"} 20615245171 (19.20 GB)
telemt_user_msgs_from_client{user="hello"} 3770
telemt_user_msgs_to_client{user="hello"} 13784
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 36254.5 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107316
telemt_connections_bad_total 1507
telemt_handshake_timeouts_total 2089
telemt_upstream_connect_attempt_total 9983
telemt_upstream_connect_success_total 9983
telemt_upstream_connect_attempts_per_request{bucket="1"} 9983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5146
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 8150
telemt_me_reconnect_success_total 8078
telemt_me_reader_eof_total 8566
telemt_me_idle_close_by_peer_total 8566
telemt_me_route_drop_no_conn_total 40048
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99349
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8153
telemt_me_writer_restored_same_endpoint_total 8058
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 99321
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 2344588276 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 52561531776 (48.95 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 36230.2 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147165
telemt_connections_bad_total 13080
telemt_handshake_timeouts_total 1099
telemt_upstream_connect_attempt_total 8008
telemt_upstream_connect_success_total 7750
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 8008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_keepalive_timeout_total 369
telemt_me_reconnect_attempts_total 33977
telemt_me_reconnect_success_total 5884
telemt_me_reader_eof_total 6900
telemt_me_idle_close_by_peer_total 6900
telemt_me_route_drop_no_conn_total 53257
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125683
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6829
telemt_me_refill_failed_total 876
telemt_me_writer_restored_same_endpoint_total 5876
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 125565
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 2231999924 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 52337022576 (48.74 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 36199.8 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90065
telemt_connections_bad_total 9487
telemt_handshake_timeouts_total 1161
telemt_upstream_connect_attempt_total 47707
telemt_upstream_connect_success_total 47263
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 47707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 50464
telemt_me_reconnect_success_total 3724
telemt_me_reader_eof_total 5182
telemt_me_idle_close_by_peer_total 5182
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13346
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35378
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5210
telemt_me_refill_failed_total 1463
telemt_me_writer_restored_same_endpoint_total 3707
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1486
telemt_user_connections_total{user="hello"} 77056
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 709096609 (676.25 MB)
telemt_user_octets_to_client{user="hello"} 22933102213 (21.36 GB)
telemt_user_msgs_from_client{user="hello"} 659167
telemt_user_msgs_to_client{user="hello"} 2510032
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 36187.0 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231316
telemt_connections_bad_total 1127
telemt_handshake_timeouts_total 1991
telemt_upstream_connect_attempt_total 7771
telemt_upstream_connect_success_total 7733
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 7771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 442
telemt_me_reconnect_attempts_total 9472
telemt_me_reconnect_success_total 5871
telemt_me_reader_eof_total 6260
telemt_me_idle_close_by_peer_total 6259
telemt_me_route_drop_no_conn_total 105770
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230778
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6060
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 5864
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 220712
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 3932532240 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 99822988760 (92.97 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 54
```