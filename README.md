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

# Server Metrics 2026-03-15 11:49:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 48904.5 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210734
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 4580
telemt_upstream_connect_attempt_total 12468
telemt_upstream_connect_success_total 12401
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13310
telemt_me_reconnect_success_total 9941
telemt_me_reader_eof_total 10630
telemt_me_idle_close_by_peer_total 10630
telemt_me_route_drop_no_conn_total 421427
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257478
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1492
telemt_desync_full_logged_total 594
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10145
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 9910
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 196735
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 3704158804 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 189598617760 (176.58 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 48910.9 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71592
telemt_connections_bad_total 2337
telemt_handshake_timeouts_total 4090
telemt_upstream_connect_attempt_total 13378
telemt_upstream_connect_success_total 13378
telemt_upstream_connect_attempts_per_request{bucket="1"} 13378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13224
telemt_me_reconnect_success_total 10891
telemt_me_reader_eof_total 11680
telemt_me_idle_close_by_peer_total 11680
telemt_me_route_drop_no_conn_total 33110
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62795
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11081
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10875
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 62794
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 1151645108 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 26248713752 (24.45 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 48903.4 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77808
telemt_connections_bad_total 1013
telemt_handshake_timeouts_total 2561
telemt_upstream_connect_attempt_total 13986
telemt_upstream_connect_success_total 13978
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 13986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 13634
telemt_me_reconnect_success_total 11497
telemt_me_reader_eof_total 12330
telemt_me_idle_close_by_peer_total 12330
telemt_me_route_drop_no_conn_total 29686
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70862
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11673
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11489
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 70779
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 9510785020 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 43315937768 (40.34 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 48903.1 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104961
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 696
telemt_upstream_connect_attempt_total 11547
telemt_upstream_connect_success_total 11546
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9139
telemt_me_reconnect_success_total 9094
telemt_me_reader_eof_total 9706
telemt_me_idle_close_by_peer_total 9706
telemt_me_route_drop_no_conn_total 41910
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95751
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 238
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9193
telemt_me_writer_restored_same_endpoint_total 9083
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 95671
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 1719854044 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 54052524056 (50.34 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 23974.6 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54285
telemt_connections_bad_total 14474
telemt_handshake_timeouts_total 849
telemt_upstream_connect_attempt_total 7925
telemt_upstream_connect_success_total 7867
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 100901
telemt_me_reconnect_success_total 6486
telemt_me_reader_eof_total 6745
telemt_me_idle_close_by_peer_total 6745
telemt_me_route_drop_no_conn_total 18982
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37739
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 70
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6474
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6382
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 37876
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 560544333 (534.58 MB)
telemt_user_octets_to_client{user="hello"} 14772294971 (13.76 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 48902.5 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276766
telemt_connections_bad_total 47654
telemt_handshake_timeouts_total 2037
telemt_upstream_connect_attempt_total 10376
telemt_upstream_connect_success_total 10313
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 10376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 7895
telemt_me_reconnect_success_total 7845
telemt_me_reader_eof_total 8354
telemt_me_idle_close_by_peer_total 8354
telemt_me_route_drop_no_conn_total 122442
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218949
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7909
telemt_me_writer_restored_same_endpoint_total 7818
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 217313
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 4815374888 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 103299366728 (96.21 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 68
```