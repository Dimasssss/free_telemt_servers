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

# Server Metrics 2026-03-13 20:26:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 132767.8 (36h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560321
telemt_connections_bad_total 15040
telemt_handshake_timeouts_total 12602
telemt_upstream_connect_attempt_total 33685
telemt_upstream_connect_success_total 33514
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 33685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5054
telemt_me_reconnect_attempts_total 31142
telemt_me_reconnect_success_total 26490
telemt_me_reader_eof_total 28279
telemt_me_idle_close_by_peer_total 28278
telemt_me_route_drop_no_conn_total 185314
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483016
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 26932
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26474
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 482911
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 8913923618 (8.30 GB)
telemt_user_octets_to_client{user="hello"} 233096555996 (217.09 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 132660.7 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282872
telemt_connections_bad_total 2101
telemt_handshake_timeouts_total 1881
telemt_upstream_connect_attempt_total 133082
telemt_upstream_connect_success_total 132108
telemt_upstream_connect_fail_total 974
telemt_upstream_connect_attempts_per_request{bucket="1"} 133082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 974
telemt_me_keepalive_timeout_total 3638
telemt_me_reconnect_attempts_total 140771
telemt_me_reconnect_success_total 26420
telemt_me_reader_eof_total 30725
telemt_me_idle_close_by_peer_total 30725
telemt_me_route_drop_no_conn_total 83897
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169416
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 34
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
telemt_me_writer_removed_unexpected_total 30238
telemt_me_refill_failed_total 3568
telemt_me_writer_restored_same_endpoint_total 26403
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3818
telemt_user_connections_total{user="hello"} 268267
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 2797114353 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 80316512164 (74.80 GB)
telemt_user_msgs_from_client{user="hello"} 1604191
telemt_user_msgs_to_client{user="hello"} 8684024
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 132624.4 (36h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329166
telemt_connections_bad_total 2644
telemt_handshake_timeouts_total 23956
telemt_upstream_connect_attempt_total 35178
telemt_upstream_connect_success_total 35173
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2805
telemt_me_reconnect_attempts_total 29742
telemt_me_reconnect_success_total 28503
telemt_me_reader_eof_total 30573
telemt_me_idle_close_by_peer_total 30573
telemt_me_route_drop_no_conn_total 117817
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291068
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 28826
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28483
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 290978
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 11847992548 (11.03 GB)
telemt_user_octets_to_client{user="hello"} 121765513584 (113.40 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 132599.7 (36h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435151
telemt_connections_bad_total 15235
telemt_handshake_timeouts_total 4176
telemt_upstream_connect_attempt_total 63338
telemt_upstream_connect_success_total 53024
telemt_upstream_connect_fail_total 10314
telemt_upstream_connect_attempts_per_request{bucket="1"} 63338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10314
telemt_me_keepalive_timeout_total 4762
telemt_me_reconnect_attempts_total 121798
telemt_me_reconnect_success_total 27365
telemt_me_reader_eof_total 31089
telemt_me_idle_close_by_peer_total 31082
telemt_me_route_drop_no_conn_total 150948
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366170
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1501
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 1055
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 571
telemt_desync_frames_bucket_total{bucket="gt_10"} 569
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30660
telemt_me_refill_failed_total 2945
telemt_me_writer_restored_same_endpoint_total 27355
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3295
telemt_user_connections_total{user="hello"} 385027
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 8703664463 (8.11 GB)
telemt_user_octets_to_client{user="hello"} 141008089220 (131.32 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 82771.3 (22h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141668
telemt_connections_bad_total 19080
telemt_handshake_timeouts_total 1440
telemt_upstream_connect_attempt_total 31442
telemt_upstream_connect_success_total 31141
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 31442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 1266
telemt_me_reconnect_attempts_total 35517
telemt_me_reconnect_success_total 22125
telemt_me_reader_eof_total 23702
telemt_me_idle_close_by_peer_total 23702
telemt_me_route_drop_no_conn_total 43850
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111748
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 22751
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22107
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 626
telemt_user_connections_total{user="hello"} 116642
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1365104301 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 52471119099 (48.87 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 132555.9 (36h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 810999
telemt_connections_bad_total 24934
telemt_handshake_timeouts_total 24964
telemt_upstream_connect_attempt_total 27362
telemt_upstream_connect_success_total 27217
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 27362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 3092
telemt_me_reconnect_attempts_total 25276
telemt_me_reconnect_success_total 20627
telemt_me_reader_eof_total 22125
telemt_me_idle_close_by_peer_total 22122
telemt_me_route_drop_no_conn_total 386132
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 760516
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 21047
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20620
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 733378
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 12847704100 (11.97 GB)
telemt_user_octets_to_client{user="hello"} 361085323712 (336.29 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 42
```