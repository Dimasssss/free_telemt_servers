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

# Server Metrics 2026-03-13 12:47:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 105256.6 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431011
telemt_connections_bad_total 3212
telemt_handshake_timeouts_total 8410
telemt_upstream_connect_attempt_total 26672
telemt_upstream_connect_success_total 26546
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 26672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2395
telemt_me_reconnect_attempts_total 24810
telemt_me_reconnect_success_total 21285
telemt_me_reader_eof_total 22724
telemt_me_idle_close_by_peer_total 22723
telemt_me_route_drop_no_conn_total 136436
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374954
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1269
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 21616
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21269
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 374546
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 6733427016 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 161508082284 (150.42 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 105149.1 (29h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199155
telemt_connections_bad_total 1659
telemt_handshake_timeouts_total 1482
telemt_upstream_connect_attempt_total 60622
telemt_upstream_connect_success_total 59914
telemt_upstream_connect_fail_total 708
telemt_upstream_connect_attempts_per_request{bucket="1"} 60622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 708
telemt_me_keepalive_timeout_total 1369
telemt_me_reconnect_attempts_total 98360
telemt_me_reconnect_success_total 25967
telemt_me_reader_eof_total 28989
telemt_me_idle_close_by_peer_total 28989
telemt_me_route_drop_no_conn_total 79239
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159428
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
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
telemt_me_writer_removed_unexpected_total 28453
telemt_me_refill_failed_total 2258
telemt_me_writer_restored_same_endpoint_total 25950
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2486
telemt_user_connections_total{user="hello"} 187908
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1917612860 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 61854423609 (57.61 GB)
telemt_user_msgs_from_client{user="hello"} 432550
telemt_user_msgs_to_client{user="hello"} 3094421
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 105112.8 (29h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242253
telemt_connections_bad_total 2065
telemt_handshake_timeouts_total 8278
telemt_upstream_connect_attempt_total 28451
telemt_upstream_connect_success_total 28447
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15244
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2207
telemt_me_reconnect_attempts_total 24361
telemt_me_reconnect_success_total 23149
telemt_me_reader_eof_total 24799
telemt_me_idle_close_by_peer_total 24799
telemt_me_route_drop_no_conn_total 89795
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223138
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 23403
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23129
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 223052
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 9395811256 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 98264349952 (91.52 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 105088.3 (29h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338153
telemt_connections_bad_total 15024
telemt_handshake_timeouts_total 2495
telemt_upstream_connect_attempt_total 40233
telemt_upstream_connect_success_total 30153
telemt_upstream_connect_fail_total 10080
telemt_upstream_connect_attempts_per_request{bucket="1"} 40233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10080
telemt_me_keepalive_timeout_total 4081
telemt_me_reconnect_attempts_total 93403
telemt_me_reconnect_success_total 21850
telemt_me_reader_eof_total 24750
telemt_me_idle_close_by_peer_total 24743
telemt_me_route_drop_no_conn_total 121914
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291343
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1031
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24358
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21840
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2508
telemt_user_connections_total{user="hello"} 294254
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 5982589750 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 110821890737 (103.21 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 55259.9 (15h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80991
telemt_connections_bad_total 10897
telemt_handshake_timeouts_total 1186
telemt_upstream_connect_attempt_total 23727
telemt_upstream_connect_success_total 23539
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 23727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 965
telemt_me_reconnect_attempts_total 25763
telemt_me_reconnect_success_total 15845
telemt_me_reader_eof_total 17013
telemt_me_idle_close_by_peer_total 17013
telemt_me_route_drop_no_conn_total 23962
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61395
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 16294
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15827
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 66304
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 571608769 (545.13 MB)
telemt_user_octets_to_client{user="hello"} 18327893659 (17.07 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 105045.0 (29h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602981
telemt_connections_bad_total 17705
telemt_handshake_timeouts_total 15226
telemt_upstream_connect_attempt_total 22269
telemt_upstream_connect_success_total 22154
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2502
telemt_me_reconnect_attempts_total 21551
telemt_me_reconnect_success_total 16929
telemt_me_reader_eof_total 18171
telemt_me_idle_close_by_peer_total 18168
telemt_me_route_drop_no_conn_total 296350
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576516
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17292
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16922
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 549565
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 9766495668 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 291729415280 (271.69 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 52
```