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

# Server Metrics 2026-03-14 19:27:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 22239.4 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119496
telemt_connections_bad_total 15815
telemt_handshake_timeouts_total 1126
telemt_upstream_connect_attempt_total 5108
telemt_upstream_connect_success_total 5106
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 3989
telemt_me_reconnect_success_total 3955
telemt_me_reader_eof_total 4189
telemt_me_idle_close_by_peer_total 4189
telemt_me_route_drop_no_conn_total 42191
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97302
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 406
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4019
telemt_me_writer_restored_same_endpoint_total 3937
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 97230
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 1910748852 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 48510379992 (45.18 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 22237.4 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48724
telemt_connections_bad_total 661
telemt_handshake_timeouts_total 905
telemt_upstream_connect_attempt_total 5818
telemt_upstream_connect_success_total 5778
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 5818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 7202
telemt_me_reconnect_success_total 4628
telemt_me_reader_eof_total 4919
telemt_me_idle_close_by_peer_total 4919
telemt_me_route_drop_no_conn_total 25685
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45355
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4771
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4623
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 45346
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 656840372 (626.41 MB)
telemt_user_octets_to_client{user="hello"} 19230574144 (17.91 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 22242.0 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53124
telemt_connections_bad_total 385
telemt_handshake_timeouts_total 1827
telemt_upstream_connect_attempt_total 7687
telemt_upstream_connect_success_total 7608
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 7687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 104002
telemt_me_reconnect_success_total 6140
telemt_me_reader_eof_total 6553
telemt_me_idle_close_by_peer_total 6553
telemt_me_route_drop_no_conn_total 20663
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48039
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 8
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 6407
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6099
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 48103
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 3136693421 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 30638923554 (28.53 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 22246.9 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68000
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 5434
telemt_upstream_connect_success_total 5400
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 4280
telemt_me_reconnect_success_total 4256
telemt_me_reader_eof_total 4464
telemt_me_idle_close_by_peer_total 4464
telemt_me_route_drop_no_conn_total 30124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64278
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 555
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 414
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4301
telemt_me_writer_restored_same_endpoint_total 4254
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 64154
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 885023760 (844.02 MB)
telemt_user_octets_to_client{user="hello"} 20000244700 (18.63 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 22239.9 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50427
telemt_connections_bad_total 4289
telemt_handshake_timeouts_total 3144
telemt_upstream_connect_attempt_total 5146
telemt_upstream_connect_success_total 5087
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 5146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 10466
telemt_me_reconnect_success_total 3936
telemt_me_reader_eof_total 4302
telemt_me_idle_close_by_peer_total 4302
telemt_me_route_drop_no_conn_total 17136
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40601
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 250
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4178
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3932
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 40589
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 628196684 (599.10 MB)
telemt_user_octets_to_client{user="hello"} 13057252380 (12.16 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 22239.5 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176094
telemt_connections_bad_total 7212
telemt_handshake_timeouts_total 2607
telemt_upstream_connect_attempt_total 4354
telemt_upstream_connect_success_total 4277
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 4354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 8128
telemt_me_reconnect_success_total 3128
telemt_me_reader_eof_total 3400
telemt_me_idle_close_by_peer_total 3400
telemt_me_route_drop_no_conn_total 99806
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161097
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3317
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3124
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 157594
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 3452853836 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 79109656320 (73.68 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 68
```