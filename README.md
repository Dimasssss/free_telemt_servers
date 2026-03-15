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

# Server Metrics 2026-03-15 19:28:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 76466.7 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359420
telemt_connections_bad_total 4381
telemt_handshake_timeouts_total 13400
telemt_upstream_connect_attempt_total 18387
telemt_upstream_connect_success_total 18294
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 18387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17896
telemt_me_reconnect_success_total 14497
telemt_me_reader_eof_total 15447
telemt_me_idle_close_by_peer_total 15447
telemt_me_route_drop_no_conn_total 473038
telemt_me_route_drop_channel_closed_total 77
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389029
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1934
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1175
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14760
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14463
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 328088
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 7416832436 (6.91 GB)
telemt_user_octets_to_client{user="hello"} 251421310864 (234.15 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 76473.2 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146159
telemt_connections_bad_total 2844
telemt_handshake_timeouts_total 12846
telemt_upstream_connect_attempt_total 20595
telemt_upstream_connect_success_total 20579
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 20595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 428
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 889
telemt_me_reconnect_attempts_total 19119
telemt_me_reconnect_success_total 16709
telemt_me_reader_eof_total 17840
telemt_me_idle_close_by_peer_total 17839
telemt_me_route_drop_no_conn_total 61620
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124657
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 17023
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16693
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 124637
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 2358866996 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 61388151644 (57.17 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 76465.6 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148346
telemt_connections_bad_total 1706
telemt_handshake_timeouts_total 3359
telemt_upstream_connect_attempt_total 22063
telemt_upstream_connect_success_total 22055
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 22063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25564
telemt_me_reconnect_success_total 18201
telemt_me_reader_eof_total 19539
telemt_me_idle_close_by_peer_total 19539
telemt_me_route_drop_no_conn_total 58200
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131072
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 18613
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18193
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 412
telemt_user_connections_total{user="hello"} 130961
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 10827688604 (10.08 GB)
telemt_user_octets_to_client{user="hello"} 71709161192 (66.78 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 76465.3 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210180
telemt_connections_bad_total 1115
telemt_handshake_timeouts_total 1516
telemt_upstream_connect_attempt_total 17949
telemt_upstream_connect_success_total 17935
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14226
telemt_me_reconnect_success_total 14141
telemt_me_reader_eof_total 15051
telemt_me_idle_close_by_peer_total 15051
telemt_me_route_drop_no_conn_total 77809
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193837
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 696
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 319
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14307
telemt_me_writer_restored_same_endpoint_total 14130
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 193755
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 3658758352 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 89139914672 (83.02 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 51536.8 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126257
telemt_connections_bad_total 25308
telemt_handshake_timeouts_total 2474
telemt_upstream_connect_attempt_total 15229
telemt_upstream_connect_success_total 15135
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 15229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106814
telemt_me_reconnect_success_total 12365
telemt_me_reader_eof_total 13001
telemt_me_idle_close_by_peer_total 13001
telemt_me_route_drop_no_conn_total 43367
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94978
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 292
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12447
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12261
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 95108
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 1549870741 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 35907175811 (33.44 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 76465.2 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517203
telemt_connections_bad_total 58011
telemt_handshake_timeouts_total 4209
telemt_upstream_connect_attempt_total 16291
telemt_upstream_connect_success_total 16198
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13682
telemt_me_reconnect_success_total 12373
telemt_me_reader_eof_total 13149
telemt_me_idle_close_by_peer_total 13149
telemt_me_route_drop_no_conn_total 336732
telemt_me_route_drop_channel_closed_total 90
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481935
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12547
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12346
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 435852
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 11136310748 (10.37 GB)
telemt_user_octets_to_client{user="hello"} 242930945092 (226.25 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 59
```