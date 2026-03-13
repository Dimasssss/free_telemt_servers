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

# Server Metrics 2026-03-13 09:05:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 91936.1 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359340
telemt_connections_bad_total 3184
telemt_handshake_timeouts_total 7779
telemt_upstream_connect_attempt_total 23276
telemt_upstream_connect_success_total 23167
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1681
telemt_me_reconnect_attempts_total 22044
telemt_me_reconnect_success_total 18534
telemt_me_reader_eof_total 19789
telemt_me_idle_close_by_peer_total 19788
telemt_me_route_drop_no_conn_total 113248
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307336
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 987
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 620
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 422
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 18837
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18518
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 307028
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 5019710556 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 138513492116 (129.00 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 91828.8 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163506
telemt_connections_bad_total 1511
telemt_handshake_timeouts_total 1233
telemt_upstream_connect_attempt_total 45909
telemt_upstream_connect_success_total 45287
telemt_upstream_connect_fail_total 622
telemt_upstream_connect_attempts_per_request{bucket="1"} 45909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 514
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 622
telemt_me_keepalive_timeout_total 703
telemt_me_reconnect_attempts_total 79598
telemt_me_reconnect_success_total 24226
telemt_me_reader_eof_total 26687
telemt_me_idle_close_by_peer_total 26687
telemt_me_route_drop_no_conn_total 62666
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137698
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
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
telemt_me_writer_removed_unexpected_total 26153
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24211
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1927
telemt_user_connections_total{user="hello"} 154190
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 1593712688 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 49569576243 (46.17 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 91792.4 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199595
telemt_connections_bad_total 2001
telemt_handshake_timeouts_total 3981
telemt_upstream_connect_attempt_total 24850
telemt_upstream_connect_success_total 24847
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 618
telemt_me_reconnect_attempts_total 21424
telemt_me_reconnect_success_total 20238
telemt_me_reader_eof_total 21703
telemt_me_idle_close_by_peer_total 21703
telemt_me_route_drop_no_conn_total 75701
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186225
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 20461
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20218
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 186150
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 6830756800 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 77461774704 (72.14 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 91767.9 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285537
telemt_connections_bad_total 13663
telemt_handshake_timeouts_total 2130
telemt_upstream_connect_attempt_total 37908
telemt_upstream_connect_success_total 27921
telemt_upstream_connect_fail_total 9987
telemt_upstream_connect_attempts_per_request{bucket="1"} 37908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9987
telemt_me_keepalive_timeout_total 3406
telemt_me_reconnect_attempts_total 74410
telemt_me_reconnect_success_total 20496
telemt_me_reader_eof_total 22819
telemt_me_idle_close_by_peer_total 22812
telemt_me_route_drop_no_conn_total 103038
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 892
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 628
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 329
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22441
telemt_me_refill_failed_total 1680
telemt_me_writer_restored_same_endpoint_total 20486
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1945
telemt_user_connections_total{user="hello"} 246182
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 5492846366 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 93678453357 (87.24 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 41939.6 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53933
telemt_connections_bad_total 8478
telemt_handshake_timeouts_total 450
telemt_upstream_connect_attempt_total 14565
telemt_upstream_connect_success_total 14421
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 14565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 347
telemt_me_reconnect_attempts_total 14539
telemt_me_reconnect_success_total 12315
telemt_me_reader_eof_total 13110
telemt_me_idle_close_by_peer_total 13110
telemt_me_route_drop_no_conn_total 16354
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43533
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12492
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12297
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 43529
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 316066404 (301.42 MB)
telemt_user_octets_to_client{user="hello"} 11935356220 (11.12 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 91724.6 (25h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491307
telemt_connections_bad_total 13399
telemt_handshake_timeouts_total 4879
telemt_upstream_connect_attempt_total 19337
telemt_upstream_connect_success_total 19234
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 18338
telemt_me_reconnect_success_total 14693
telemt_me_reader_eof_total 15784
telemt_me_idle_close_by_peer_total 15781
telemt_me_route_drop_no_conn_total 257301
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482584
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 397
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 14997
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14686
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 455679
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 8353531920 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 258314952592 (240.57 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 76
```