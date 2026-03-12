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

# Server Metrics 2026-03-12 23:52:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 58769.6 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252849
telemt_connections_bad_total 2745
telemt_handshake_timeouts_total 5262
telemt_upstream_connect_attempt_total 14810
telemt_upstream_connect_success_total 14745
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 14810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1487
telemt_me_reconnect_attempts_total 15231
telemt_me_reconnect_success_total 11760
telemt_me_reader_eof_total 12539
telemt_me_idle_close_by_peer_total 12538
telemt_me_route_drop_no_conn_total 78685
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209061
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12001
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11744
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 208829
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 3856922692 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 106964189796 (99.62 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 58662.7 (16h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115646
telemt_connections_bad_total 647
telemt_handshake_timeouts_total 905
telemt_upstream_connect_attempt_total 33656
telemt_upstream_connect_success_total 33272
telemt_upstream_connect_fail_total 384
telemt_upstream_connect_attempts_per_request{bucket="1"} 33656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 384
telemt_me_keepalive_timeout_total 415
telemt_me_reconnect_attempts_total 55672
telemt_me_reconnect_success_total 13800
telemt_me_reader_eof_total 15480
telemt_me_idle_close_by_peer_total 15480
telemt_me_route_drop_no_conn_total 41925
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93319
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 15207
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 13785
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1407
telemt_user_connections_total{user="hello"} 109821
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 1208976172 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 34067454947 (31.73 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 58626.4 (16h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141350
telemt_connections_bad_total 1663
telemt_handshake_timeouts_total 2240
telemt_upstream_connect_attempt_total 16110
telemt_upstream_connect_success_total 16109
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 14247
telemt_me_reconnect_success_total 13097
telemt_me_reader_eof_total 13982
telemt_me_idle_close_by_peer_total 13982
telemt_me_route_drop_no_conn_total 53397
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132148
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 13261
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13077
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 132114
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 2609197960 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 60705296876 (56.54 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 58601.9 (16h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204589
telemt_connections_bad_total 13279
telemt_handshake_timeouts_total 1382
telemt_upstream_connect_attempt_total 27693
telemt_upstream_connect_success_total 17972
telemt_upstream_connect_fail_total 9720
telemt_upstream_connect_attempts_per_request{bucket="1"} 27692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9720
telemt_me_keepalive_timeout_total 2736
telemt_me_reconnect_attempts_total 44399
telemt_me_reconnect_success_total 12147
telemt_me_reader_eof_total 13597
telemt_me_idle_close_by_peer_total 13590
telemt_me_route_drop_no_conn_total 72705
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168549
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13341
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 12137
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1194
telemt_user_connections_total{user="hello"} 171303
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2991873398 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 69879630045 (65.08 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8773.5 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7699
telemt_connections_bad_total 1625
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2809
telemt_upstream_connect_success_total 2781
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 2809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 2326
telemt_me_reconnect_success_total 2322
telemt_me_reader_eof_total 2458
telemt_me_idle_close_by_peer_total 2458
telemt_me_route_drop_no_conn_total 2281
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5806
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2334
telemt_me_writer_restored_same_endpoint_total 2306
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 5806
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 19961108 (19.04 MB)
telemt_user_octets_to_client{user="hello"} 2009930060 (1.87 GB)
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 58558.3 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337961
telemt_connections_bad_total 5149
telemt_handshake_timeouts_total 2537
telemt_upstream_connect_attempt_total 12301
telemt_upstream_connect_success_total 12233
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 600
telemt_me_reconnect_attempts_total 12914
telemt_me_reconnect_success_total 9299
telemt_me_reader_eof_total 9947
telemt_me_idle_close_by_peer_total 9945
telemt_me_route_drop_no_conn_total 151278
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332186
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9525
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9292
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 320489
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 5529571192 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 172534807300 (160.69 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 27
```