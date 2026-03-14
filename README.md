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

# Server Metrics 2026-03-14 19:42:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 23160.0 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123478
telemt_connections_bad_total 15881
telemt_handshake_timeouts_total 1171
telemt_upstream_connect_attempt_total 5266
telemt_upstream_connect_success_total 5264
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4104
telemt_me_reconnect_success_total 4069
telemt_me_reader_eof_total 4310
telemt_me_idle_close_by_peer_total 4310
telemt_me_route_drop_no_conn_total 43850
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101004
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 415
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 263
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4135
telemt_me_writer_restored_same_endpoint_total 4051
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 100925
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 2067399716 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 51028335124 (47.52 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 23157.9 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50030
telemt_connections_bad_total 668
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 6033
telemt_upstream_connect_success_total 5992
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 7373
telemt_me_reconnect_success_total 4797
telemt_me_reader_eof_total 5102
telemt_me_idle_close_by_peer_total 5102
telemt_me_route_drop_no_conn_total 26606
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46590
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4944
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4792
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 46582
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 1143562488 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 19625749228 (18.28 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 23162.5 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55287
telemt_connections_bad_total 385
telemt_handshake_timeouts_total 1859
telemt_upstream_connect_attempt_total 7925
telemt_upstream_connect_success_total 7842
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 7925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 104191
telemt_me_reconnect_success_total 6328
telemt_me_reader_eof_total 6748
telemt_me_idle_close_by_peer_total 6748
telemt_me_route_drop_no_conn_total 21410
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50072
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 6595
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6286
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 50140
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 3212249213 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 36736493430 (34.21 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 23167.1 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70713
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 568
telemt_upstream_connect_attempt_total 5637
telemt_upstream_connect_success_total 5603
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 4440
telemt_me_reconnect_success_total 4416
telemt_me_reader_eof_total 4637
telemt_me_idle_close_by_peer_total 4637
telemt_me_route_drop_no_conn_total 31142
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66935
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4463
telemt_me_writer_restored_same_endpoint_total 4414
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 66811
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 945070704 (901.29 MB)
telemt_user_octets_to_client{user="hello"} 21265559736 (19.81 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 23160.3 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52290
telemt_connections_bad_total 4463
telemt_handshake_timeouts_total 3215
telemt_upstream_connect_attempt_total 5361
telemt_upstream_connect_success_total 5301
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 5361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 10637
telemt_me_reconnect_success_total 4106
telemt_me_reader_eof_total 4485
telemt_me_idle_close_by_peer_total 4485
telemt_me_route_drop_no_conn_total 17791
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42146
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4350
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4102
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 42134
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 667642300 (636.71 MB)
telemt_user_octets_to_client{user="hello"} 15305605416 (14.25 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 23159.9 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181723
telemt_connections_bad_total 7213
telemt_handshake_timeouts_total 2615
telemt_upstream_connect_attempt_total 4528
telemt_upstream_connect_success_total 4450
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 4528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 8258
telemt_me_reconnect_success_total 3257
telemt_me_reader_eof_total 3539
telemt_me_idle_close_by_peer_total 3539
telemt_me_route_drop_no_conn_total 102758
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166576
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3449
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3253
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 163065
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 3506811932 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 81311461140 (75.73 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 50
```