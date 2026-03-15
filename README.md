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

# Server Metrics 2026-03-15 14:12:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 57480.3 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258205
telemt_connections_bad_total 2364
telemt_handshake_timeouts_total 6011
telemt_upstream_connect_attempt_total 14540
telemt_upstream_connect_success_total 14465
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 14975
telemt_me_reconnect_success_total 11597
telemt_me_reader_eof_total 12356
telemt_me_idle_close_by_peer_total 12356
telemt_me_route_drop_no_conn_total 437533
telemt_me_route_drop_channel_closed_total 71
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300931
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1689
telemt_desync_full_logged_total 669
telemt_desync_suppressed_total 1020
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 727
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11821
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11566
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 240036
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 5285102592 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 209099857308 (194.74 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 57488.7 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95052
telemt_connections_bad_total 2755
telemt_handshake_timeouts_total 9213
telemt_upstream_connect_attempt_total 15822
telemt_upstream_connect_success_total 15822
telemt_upstream_connect_attempts_per_request{bucket="1"} 15822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15272
telemt_me_reconnect_success_total 12924
telemt_me_reader_eof_total 13819
telemt_me_idle_close_by_peer_total 13819
telemt_me_route_drop_no_conn_total 40389
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80233
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 13147
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12908
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 80224
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1590755888 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 38520682860 (35.88 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 57480.6 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103092
telemt_connections_bad_total 1642
telemt_handshake_timeouts_total 2767
telemt_upstream_connect_attempt_total 17085
telemt_upstream_connect_success_total 17077
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 18793
telemt_me_reconnect_success_total 14174
telemt_me_reader_eof_total 15168
telemt_me_idle_close_by_peer_total 15168
telemt_me_route_drop_no_conn_total 38569
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88997
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14450
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 14166
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 88902
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 10109933820 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 52755338280 (49.13 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 57480.1 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136207
telemt_connections_bad_total 736
telemt_handshake_timeouts_total 891
telemt_upstream_connect_attempt_total 13631
telemt_upstream_connect_success_total 13628
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10824
telemt_me_reconnect_success_total 10760
telemt_me_reader_eof_total 11461
telemt_me_idle_close_by_peer_total 11461
telemt_me_route_drop_no_conn_total 52991
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124291
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 422
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10884
telemt_me_writer_restored_same_endpoint_total 10749
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 124207
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 2340398016 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 62240818772 (57.97 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 32551.6 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78529
telemt_connections_bad_total 21124
telemt_handshake_timeouts_total 1413
telemt_upstream_connect_attempt_total 10330
telemt_upstream_connect_success_total 10264
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 102855
telemt_me_reconnect_success_total 8430
telemt_me_reader_eof_total 8814
telemt_me_idle_close_by_peer_total 8814
telemt_me_route_drop_no_conn_total 26408
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54224
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 151
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 8442
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8326
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 54361
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 831470393 (792.95 MB)
telemt_user_octets_to_client{user="hello"} 22105288271 (20.59 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 57479.5 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343449
telemt_connections_bad_total 48369
telemt_handshake_timeouts_total 2824
telemt_upstream_connect_attempt_total 12317
telemt_upstream_connect_success_total 12244
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 12317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 9428
telemt_me_reconnect_success_total 9359
telemt_me_reader_eof_total 9935
telemt_me_idle_close_by_peer_total 9935
telemt_me_route_drop_no_conn_total 158315
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282209
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 296
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9448
telemt_me_writer_restored_same_endpoint_total 9332
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 280066
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 6857724720 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 138043141052 (128.56 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 74
```