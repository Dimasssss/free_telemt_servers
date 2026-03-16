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

# Server Metrics 2026-03-16 06:27:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 115977.6 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522400
telemt_connections_bad_total 5559
telemt_handshake_timeouts_total 18549
telemt_upstream_connect_attempt_total 27428
telemt_upstream_connect_success_total 27301
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 27428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25005
telemt_me_reconnect_success_total 21575
telemt_me_reader_eof_total 23086
telemt_me_idle_close_by_peer_total 23086
telemt_me_route_drop_no_conn_total 515176
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521664
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2536
telemt_desync_full_logged_total 1015
telemt_desync_suppressed_total 1521
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 1033
telemt_pool_swap_total 112
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21918
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21541
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 460511
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 9162846048 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 308127801892 (286.97 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 115984.2 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205256
telemt_connections_bad_total 3122
telemt_handshake_timeouts_total 14917
telemt_upstream_connect_attempt_total 31235
telemt_upstream_connect_success_total 31160
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 31235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 31931
telemt_me_reconnect_success_total 25015
telemt_me_reader_eof_total 26812
telemt_me_idle_close_by_peer_total 26811
telemt_me_route_drop_no_conn_total 102583
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179735
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
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 25573
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 24999
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 179273
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 3962774641 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 92480661084 (86.13 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 115976.8 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224547
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 4408
telemt_upstream_connect_attempt_total 32454
telemt_upstream_connect_success_total 32446
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 32454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34049
telemt_me_reconnect_success_total 26652
telemt_me_reader_eof_total 28688
telemt_me_idle_close_by_peer_total 28687
telemt_me_route_drop_no_conn_total 79468
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178673
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
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 27142
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26644
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 178389
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 17176255033 (16.00 GB)
telemt_user_octets_to_client{user="hello"} 107883728392 (100.47 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 115976.5 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300080
telemt_connections_bad_total 1306
telemt_handshake_timeouts_total 2796
telemt_upstream_connect_attempt_total 27000
telemt_upstream_connect_success_total 26973
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 27000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21370
telemt_me_reconnect_success_total 21241
telemt_me_reader_eof_total 22681
telemt_me_idle_close_by_peer_total 22680
telemt_me_route_drop_no_conn_total 108002
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275655
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 961
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 623
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 21508
telemt_me_writer_restored_same_endpoint_total 21230
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 275542
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 4611533628 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 121144517092 (112.82 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 91047.8 (25h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201958
telemt_connections_bad_total 35048
telemt_handshake_timeouts_total 3571
telemt_upstream_connect_attempt_total 25921
telemt_upstream_connect_success_total 25779
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 25921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115556
telemt_me_reconnect_success_total 21073
telemt_me_reader_eof_total 22384
telemt_me_idle_close_by_peer_total 22384
telemt_me_route_drop_no_conn_total 63446
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158216
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 419
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 21243
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 20969
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 157848
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 2114948189 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 69216072459 (64.46 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 115975.8 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749754
telemt_connections_bad_total 64450
telemt_handshake_timeouts_total 5595
telemt_upstream_connect_attempt_total 24466
telemt_upstream_connect_success_total 24335
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 24466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19917
telemt_me_reconnect_success_total 18575
telemt_me_reader_eof_total 19835
telemt_me_idle_close_by_peer_total 19835
telemt_me_route_drop_no_conn_total 621651
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 757473
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
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 18834
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18548
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 616130
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 13845247528 (12.89 GB)
telemt_user_octets_to_client{user="hello"} 375286793808 (349.51 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 71
```