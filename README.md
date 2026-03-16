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

# Server Metrics 2026-03-16 06:37:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 116589.1 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526809
telemt_connections_bad_total 5681
telemt_handshake_timeouts_total 18805
telemt_upstream_connect_attempt_total 27547
telemt_upstream_connect_success_total 27418
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 27547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25079
telemt_me_reconnect_success_total 21649
telemt_me_reader_eof_total 23164
telemt_me_idle_close_by_peer_total 23164
telemt_me_route_drop_no_conn_total 516435
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525544
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2558
telemt_desync_full_logged_total 1022
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 999
telemt_desync_frames_bucket_total{bucket="gt_10"} 1042
telemt_pool_swap_total 113
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21992
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21615
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 464390
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 9225351744 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 310186998208 (288.88 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 116596.4 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207229
telemt_connections_bad_total 3122
telemt_handshake_timeouts_total 14924
telemt_upstream_connect_attempt_total 31401
telemt_upstream_connect_success_total 31326
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 31401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 610
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32053
telemt_me_reconnect_success_total 25136
telemt_me_reader_eof_total 26946
telemt_me_idle_close_by_peer_total 26945
telemt_me_route_drop_no_conn_total 103319
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181662
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 25694
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25120
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 181197
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 4012473925 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 94500595560 (88.01 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 116588.7 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227393
telemt_connections_bad_total 5098
telemt_handshake_timeouts_total 4559
telemt_upstream_connect_attempt_total 32651
telemt_upstream_connect_success_total 32643
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 32651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34203
telemt_me_reconnect_success_total 26806
telemt_me_reader_eof_total 28863
telemt_me_idle_close_by_peer_total 28862
telemt_me_route_drop_no_conn_total 80012
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180185
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 27296
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26798
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 179902
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 17240512289 (16.06 GB)
telemt_user_octets_to_client{user="hello"} 108282590828 (100.85 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 116588.5 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303402
telemt_connections_bad_total 1312
telemt_handshake_timeouts_total 2828
telemt_upstream_connect_attempt_total 27146
telemt_upstream_connect_success_total 27117
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21470
telemt_me_reconnect_success_total 21338
telemt_me_reader_eof_total 22791
telemt_me_idle_close_by_peer_total 22790
telemt_me_route_drop_no_conn_total 108776
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278838
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 970
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 629
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 417
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21608
telemt_me_writer_restored_same_endpoint_total 21327
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 278724
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 4631838240 (4.31 GB)
telemt_user_octets_to_client{user="hello"} 122131667000 (113.74 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 91659.9 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204093
telemt_connections_bad_total 35166
telemt_handshake_timeouts_total 3594
telemt_upstream_connect_attempt_total 26142
telemt_upstream_connect_success_total 26000
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 26142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115777
telemt_me_reconnect_success_total 21292
telemt_me_reader_eof_total 22604
telemt_me_idle_close_by_peer_total 22604
telemt_me_route_drop_no_conn_total 64243
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160058
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 430
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 328
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 21463
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 21188
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 159689
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 2150452989 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 69539960715 (64.76 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 116587.8 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754374
telemt_connections_bad_total 64718
telemt_handshake_timeouts_total 5612
telemt_upstream_connect_attempt_total 24609
telemt_upstream_connect_success_total 24477
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 24609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20016
telemt_me_reconnect_success_total 18674
telemt_me_reader_eof_total 19945
telemt_me_idle_close_by_peer_total 19945
telemt_me_route_drop_no_conn_total 623517
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 761670
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 18934
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18647
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 620321
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 13902542800 (12.95 GB)
telemt_user_octets_to_client{user="hello"} 376917852356 (351.03 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 73
```