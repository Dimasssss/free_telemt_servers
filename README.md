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

# Server Metrics 2026-03-12 16:18:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31480.5 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166523
telemt_connections_bad_total 2028
telemt_handshake_timeouts_total 4778
telemt_upstream_connect_attempt_total 7717
telemt_upstream_connect_success_total 7688
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 294
telemt_me_reconnect_attempts_total 6128
telemt_me_reconnect_success_total 6084
telemt_me_reader_eof_total 6390
telemt_me_idle_close_by_peer_total 6389
telemt_me_route_drop_no_conn_total 48572
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143054
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 620
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6143
telemt_me_writer_restored_same_endpoint_total 6068
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 143012
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 2400904476 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 55064911340 (51.28 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31373.6 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69659
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 572
telemt_upstream_connect_attempt_total 10098
telemt_upstream_connect_success_total 9889
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 10098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 29013
telemt_me_reconnect_success_total 8308
telemt_me_reader_eof_total 9117
telemt_me_idle_close_by_peer_total 9117
telemt_me_route_drop_no_conn_total 30862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66177
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_me_writer_removed_unexpected_total 9015
telemt_me_refill_failed_total 646
telemt_me_writer_restored_same_endpoint_total 8293
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 707
telemt_user_connections_total{user="hello"} 66166
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 726977856 (693.30 MB)
telemt_user_octets_to_client{user="hello"} 18604607404 (17.33 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31337.0 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95023
telemt_connections_bad_total 1488
telemt_handshake_timeouts_total 1932
telemt_upstream_connect_attempt_total 8585
telemt_upstream_connect_success_total 8585
telemt_upstream_connect_attempts_per_request{bucket="1"} 8585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 7016
telemt_me_reconnect_success_total 6953
telemt_me_reader_eof_total 7351
telemt_me_idle_close_by_peer_total 7351
telemt_me_route_drop_no_conn_total 34932
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87685
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7014
telemt_me_writer_restored_same_endpoint_total 6933
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 87659
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 2189460876 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 44170634188 (41.14 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31312.8 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130104
telemt_connections_bad_total 13063
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 7151
telemt_upstream_connect_success_total 6936
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 7151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 29303
telemt_me_reconnect_success_total 5345
telemt_me_reader_eof_total 6228
telemt_me_idle_close_by_peer_total 6228
telemt_me_route_drop_no_conn_total 45850
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109316
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 385
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6155
telemt_me_refill_failed_total 747
telemt_me_writer_restored_same_endpoint_total 5337
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 810
telemt_user_connections_total{user="hello"} 109196
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 2085165036 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 46332773064 (43.15 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31282.4 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74021
telemt_connections_bad_total 6423
telemt_handshake_timeouts_total 1087
telemt_upstream_connect_attempt_total 36357
telemt_upstream_connect_success_total 35972
telemt_upstream_connect_fail_total 384
telemt_upstream_connect_attempts_per_request{bucket="1"} 36356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 384
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 42415
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4891
telemt_me_idle_close_by_peer_total 4891
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34123
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 10
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
telemt_me_writer_removed_unexpected_total 4917
telemt_me_refill_failed_total 1213
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1233
telemt_user_connections_total{user="hello"} 64819
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 580419688 (553.53 MB)
telemt_user_octets_to_client{user="hello"} 19464631583 (18.13 GB)
telemt_user_msgs_from_client{user="hello"} 491289
telemt_user_msgs_to_client{user="hello"} 1913554
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31269.6 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195829
telemt_connections_bad_total 955
telemt_handshake_timeouts_total 1529
telemt_upstream_connect_attempt_total 6686
telemt_upstream_connect_success_total 6653
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 6130
telemt_me_reconnect_success_total 5062
telemt_me_reader_eof_total 5334
telemt_me_idle_close_by_peer_total 5333
telemt_me_route_drop_no_conn_total 75898
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187315
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5160
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5055
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 187268
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 3556501320 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 82703690584 (77.02 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 53
```