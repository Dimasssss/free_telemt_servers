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

# Server Metrics 2026-03-13 05:15:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 78110.4 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296995
telemt_connections_bad_total 3065
telemt_handshake_timeouts_total 5992
telemt_upstream_connect_attempt_total 19695
telemt_upstream_connect_success_total 19603
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 19695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1560
telemt_me_reconnect_attempts_total 19184
telemt_me_reconnect_success_total 15687
telemt_me_reader_eof_total 16772
telemt_me_idle_close_by_peer_total 16771
telemt_me_route_drop_no_conn_total 92504
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 850
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15965
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15671
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 249816
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 4287210132 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 121897403588 (113.53 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 78003.4 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136025
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1032
telemt_upstream_connect_attempt_total 41601
telemt_upstream_connect_success_total 41082
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 41601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 67247
telemt_me_reconnect_success_total 20684
telemt_me_reader_eof_total 22788
telemt_me_idle_close_by_peer_total 22788
telemt_me_route_drop_no_conn_total 50398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112729
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 22303
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20669
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 129229
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 1344785340 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 39225959607 (36.53 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 77967.0 (21h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164318
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 2661
telemt_upstream_connect_attempt_total 21515
telemt_upstream_connect_success_total 21513
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 460
telemt_me_reconnect_attempts_total 18742
telemt_me_reconnect_success_total 17577
telemt_me_reader_eof_total 18828
telemt_me_idle_close_by_peer_total 18828
telemt_me_route_drop_no_conn_total 63776
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153717
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
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17767
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17557
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 153644
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 2903180996 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 70886311868 (66.02 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 77942.7 (21h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237624
telemt_connections_bad_total 13564
telemt_handshake_timeouts_total 1780
telemt_upstream_connect_attempt_total 33816
telemt_upstream_connect_success_total 23924
telemt_upstream_connect_fail_total 9892
telemt_upstream_connect_attempts_per_request{bucket="1"} 33816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9892
telemt_me_keepalive_timeout_total 3314
telemt_me_reconnect_attempts_total 67322
telemt_me_reconnect_success_total 17168
telemt_me_reader_eof_total 19258
telemt_me_idle_close_by_peer_total 19251
telemt_me_route_drop_no_conn_total 86395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198963
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 555
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 205
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18959
telemt_me_refill_failed_total 1563
telemt_me_writer_restored_same_endpoint_total 17158
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1791
telemt_user_connections_total{user="hello"} 201707
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 3276556686 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 80791636237 (75.24 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28114.3 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29478
telemt_connections_bad_total 5287
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 9258
telemt_upstream_connect_success_total 9167
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 9258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 8693
telemt_me_reconnect_success_total 7735
telemt_me_reader_eof_total 8257
telemt_me_idle_close_by_peer_total 8257
telemt_me_route_drop_no_conn_total 8145
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23252
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7838
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 7717
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 23252
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 194916972 (185.89 MB)
telemt_user_octets_to_client{user="hello"} 9348052984 (8.71 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 77899.3 (21h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399168
telemt_connections_bad_total 7738
telemt_handshake_timeouts_total 2966
telemt_upstream_connect_attempt_total 16593
telemt_upstream_connect_success_total 16500
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1447
telemt_me_reconnect_attempts_total 16254
telemt_me_reconnect_success_total 12623
telemt_me_reader_eof_total 13555
telemt_me_idle_close_by_peer_total 13552
telemt_me_route_drop_no_conn_total 177918
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388749
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 331
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 12898
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12616
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 376991
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 6241155264 (5.81 GB)
telemt_user_octets_to_client{user="hello"} 221617759260 (206.40 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 47
```