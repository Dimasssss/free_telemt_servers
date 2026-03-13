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

# Server Metrics 2026-03-13 15:50:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 116252.4 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482788
telemt_connections_bad_total 3496
telemt_handshake_timeouts_total 8840
telemt_upstream_connect_attempt_total 29035
telemt_upstream_connect_success_total 28895
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2480
telemt_me_reconnect_attempts_total 26599
telemt_me_reconnect_success_total 23064
telemt_me_reader_eof_total 24643
telemt_me_idle_close_by_peer_total 24642
telemt_me_route_drop_no_conn_total 157682
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 895
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 23417
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23048
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 423418
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 7548198820 (7.03 GB)
telemt_user_octets_to_client{user="hello"} 197726865156 (184.15 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 116146.3 (32h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232243
telemt_connections_bad_total 1840
telemt_handshake_timeouts_total 1677
telemt_upstream_connect_attempt_total 89214
telemt_upstream_connect_success_total 88425
telemt_upstream_connect_fail_total 788
telemt_upstream_connect_attempts_per_request{bucket="1"} 89213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 993
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 788
telemt_me_keepalive_timeout_total 1407
telemt_me_reconnect_attempts_total 114932
telemt_me_reconnect_success_total 26023
telemt_me_reader_eof_total 29558
telemt_me_idle_close_by_peer_total 29558
telemt_me_route_drop_no_conn_total 81623
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163278
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
telemt_me_writer_removed_unexpected_total 29025
telemt_me_refill_failed_total 2774
telemt_me_writer_restored_same_endpoint_total 26006
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3002
telemt_user_connections_total{user="hello"} 219683
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 2252659034 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 69105785904 (64.36 GB)
telemt_user_msgs_from_client{user="hello"} 866662
telemt_user_msgs_to_client{user="hello"} 5397447
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 116109.4 (32h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279837
telemt_connections_bad_total 2437
telemt_handshake_timeouts_total 13335
telemt_upstream_connect_attempt_total 31097
telemt_upstream_connect_success_total 31093
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2347
telemt_me_reconnect_attempts_total 26485
telemt_me_reconnect_success_total 25264
telemt_me_reader_eof_total 27074
telemt_me_idle_close_by_peer_total 27074
telemt_me_route_drop_no_conn_total 101215
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254121
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
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 25544
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25244
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 254036
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 9657777608 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 107699276644 (100.30 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 116084.5 (32h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380693
telemt_connections_bad_total 15057
telemt_handshake_timeouts_total 3770
telemt_upstream_connect_attempt_total 43012
telemt_upstream_connect_success_total 32838
telemt_upstream_connect_fail_total 10174
telemt_upstream_connect_attempts_per_request{bucket="1"} 43012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10174
telemt_me_keepalive_timeout_total 4166
telemt_me_reconnect_attempts_total 104080
telemt_me_reconnect_success_total 24007
telemt_me_reader_eof_total 27217
telemt_me_idle_close_by_peer_total 27210
telemt_me_route_drop_no_conn_total 136406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330219
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1325
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 933
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 497
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26816
telemt_me_refill_failed_total 2497
telemt_me_writer_restored_same_endpoint_total 23997
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2809
telemt_user_connections_total{user="hello"} 333130
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 6936695278 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 124114996821 (115.59 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 66256.0 (18h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103631
telemt_connections_bad_total 13238
telemt_handshake_timeouts_total 1316
telemt_upstream_connect_attempt_total 26797
telemt_upstream_connect_success_total 26564
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 26797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 1049
telemt_me_reconnect_attempts_total 29516
telemt_me_reconnect_success_total 18343
telemt_me_reader_eof_total 19676
telemt_me_idle_close_by_peer_total 19676
telemt_me_route_drop_no_conn_total 31855
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80818
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
telemt_me_writer_removed_unexpected_total 18849
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18325
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 85717
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 994074957 (948.02 MB)
telemt_user_octets_to_client{user="hello"} 26227336659 (24.43 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 116041.7 (32h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702033
telemt_connections_bad_total 23658
telemt_handshake_timeouts_total 23181
telemt_upstream_connect_attempt_total 24297
telemt_upstream_connect_success_total 24175
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 24297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 2555
telemt_me_reconnect_attempts_total 23052
telemt_me_reconnect_success_total 18424
telemt_me_reader_eof_total 19769
telemt_me_idle_close_by_peer_total 19766
telemt_me_route_drop_no_conn_total 331870
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 659136
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 661
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18803
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18417
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 632085
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 10654193284 (9.92 GB)
telemt_user_octets_to_client{user="hello"} 325854254140 (303.48 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 71
```