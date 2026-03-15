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

# Server Metrics 2026-03-15 17:51:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 70650.2 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330482
telemt_connections_bad_total 4182
telemt_handshake_timeouts_total 10037
telemt_upstream_connect_attempt_total 17202
telemt_upstream_connect_success_total 17115
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 17202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16977
telemt_me_reconnect_success_total 13581
telemt_me_reader_eof_total 14463
telemt_me_idle_close_by_peer_total 14463
telemt_me_route_drop_no_conn_total 461320
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364448
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1854
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1117
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 727
telemt_desync_frames_bucket_total{bucket="gt_10"} 781
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13831
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13547
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 303547
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 6226088020 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 240462223932 (223.95 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 70656.6 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132215
telemt_connections_bad_total 2832
telemt_handshake_timeouts_total 11999
telemt_upstream_connect_attempt_total 19242
telemt_upstream_connect_success_total 19242
telemt_upstream_connect_attempts_per_request{bucket="1"} 19242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 293
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18031
telemt_me_reconnect_success_total 15666
telemt_me_reader_eof_total 16746
telemt_me_idle_close_by_peer_total 16745
telemt_me_route_drop_no_conn_total 54648
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111931
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
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15940
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15650
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 111912
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 2115960592 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 55406593016 (51.60 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 70649.0 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136208
telemt_connections_bad_total 1696
telemt_handshake_timeouts_total 3258
telemt_upstream_connect_attempt_total 20743
telemt_upstream_connect_success_total 20735
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24502
telemt_me_reconnect_success_total 17145
telemt_me_reader_eof_total 18403
telemt_me_idle_close_by_peer_total 18403
telemt_me_route_drop_no_conn_total 53294
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119607
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 17540
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17137
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 395
telemt_user_connections_total{user="hello"} 119500
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 10687816060 (9.95 GB)
telemt_user_octets_to_client{user="hello"} 67712644696 (63.06 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 70648.7 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185468
telemt_connections_bad_total 936
telemt_handshake_timeouts_total 1233
telemt_upstream_connect_attempt_total 16783
telemt_upstream_connect_success_total 16771
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13320
telemt_me_reconnect_success_total 13237
telemt_me_reader_eof_total 14088
telemt_me_idle_close_by_peer_total 14088
telemt_me_route_drop_no_conn_total 71033
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171224
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13399
telemt_me_writer_restored_same_endpoint_total 13226
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 171136
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 3194711856 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 77216260880 (71.91 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 45720.3 (12h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112953
telemt_connections_bad_total 23701
telemt_handshake_timeouts_total 2448
telemt_upstream_connect_attempt_total 13714
telemt_upstream_connect_success_total 13635
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105617
telemt_me_reconnect_success_total 11174
telemt_me_reader_eof_total 11732
telemt_me_idle_close_by_peer_total 11732
telemt_me_route_drop_no_conn_total 38717
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83679
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 226
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11238
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11070
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 83812
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 1403637689 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 32874528975 (30.62 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 70648.3 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472021
telemt_connections_bad_total 57628
telemt_handshake_timeouts_total 3858
telemt_upstream_connect_attempt_total 15301
telemt_upstream_connect_success_total 15210
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12952
telemt_me_reconnect_success_total 11648
telemt_me_reader_eof_total 12374
telemt_me_idle_close_by_peer_total 12374
telemt_me_route_drop_no_conn_total 295539
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430280
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11811
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11621
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 393251
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 10338304876 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 210274437860 (195.83 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 78
```