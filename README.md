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

# Server Metrics 2026-03-13 13:43:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 108614.4 (30h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447564
telemt_connections_bad_total 3215
telemt_handshake_timeouts_total 8489
telemt_upstream_connect_attempt_total 27435
telemt_upstream_connect_success_total 27306
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 27435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2409
telemt_me_reconnect_attempts_total 25398
telemt_me_reconnect_success_total 21870
telemt_me_reader_eof_total 23357
telemt_me_idle_close_by_peer_total 23356
telemt_me_route_drop_no_conn_total 143749
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390740
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1313
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 22209
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21854
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 390321
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 7096917340 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 176533164664 (164.41 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 108508.1 (30h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209409
telemt_connections_bad_total 1682
telemt_handshake_timeouts_total 1519
telemt_upstream_connect_attempt_total 69326
telemt_upstream_connect_success_total 68595
telemt_upstream_connect_fail_total 731
telemt_upstream_connect_attempts_per_request{bucket="1"} 69326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 650
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 731
telemt_me_keepalive_timeout_total 1389
telemt_me_reconnect_attempts_total 103905
telemt_me_reconnect_success_total 26005
telemt_me_reader_eof_total 29199
telemt_me_idle_close_by_peer_total 29199
telemt_me_route_drop_no_conn_total 79857
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160862
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 25
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
telemt_me_writer_removed_unexpected_total 28663
telemt_me_refill_failed_total 2430
telemt_me_writer_restored_same_endpoint_total 25988
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2658
telemt_user_connections_total{user="hello"} 197810
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2011529451 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 64144722042 (59.74 GB)
telemt_user_msgs_from_client{user="hello"} 550737
telemt_user_msgs_to_client{user="hello"} 3865662
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 108471.7 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254594
telemt_connections_bad_total 2079
telemt_handshake_timeouts_total 10118
telemt_upstream_connect_attempt_total 29212
telemt_upstream_connect_success_total 29208
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2265
telemt_me_reconnect_attempts_total 24949
telemt_me_reconnect_success_total 23735
telemt_me_reader_eof_total 25429
telemt_me_idle_close_by_peer_total 25429
telemt_me_route_drop_no_conn_total 92808
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233157
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
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 23992
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23715
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 233075
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 9458495472 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 100448328060 (93.55 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 108447.3 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352256
telemt_connections_bad_total 15036
telemt_handshake_timeouts_total 3418
telemt_upstream_connect_attempt_total 41172
telemt_upstream_connect_success_total 31055
telemt_upstream_connect_fail_total 10117
telemt_upstream_connect_attempts_per_request{bucket="1"} 41172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10117
telemt_me_keepalive_timeout_total 4128
telemt_me_reconnect_attempts_total 96403
telemt_me_reconnect_success_total 22576
telemt_me_reader_eof_total 25559
telemt_me_idle_close_by_peer_total 25552
telemt_me_route_drop_no_conn_total 126189
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303510
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1136
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 802
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 428
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 25169
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 22566
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2593
telemt_user_connections_total{user="hello"} 306420
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 6663089518 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 114699024221 (106.82 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 58618.8 (16h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87754
telemt_connections_bad_total 11752
telemt_handshake_timeouts_total 1204
telemt_upstream_connect_attempt_total 24547
telemt_upstream_connect_success_total 24350
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 24547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 1002
telemt_me_reconnect_attempts_total 26402
telemt_me_reconnect_success_total 16483
telemt_me_reader_eof_total 17695
telemt_me_idle_close_by_peer_total 17695
telemt_me_route_drop_no_conn_total 26217
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67091
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 16936
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16465
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 71991
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 881667169 (840.82 MB)
telemt_user_octets_to_client{user="hello"} 21286008023 (19.82 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 108403.8 (30h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 631304
telemt_connections_bad_total 17946
telemt_handshake_timeouts_total 18017
telemt_upstream_connect_attempt_total 22902
telemt_upstream_connect_success_total 22784
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 22902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2506
telemt_me_reconnect_attempts_total 22009
telemt_me_reconnect_success_total 17385
telemt_me_reader_eof_total 18666
telemt_me_idle_close_by_peer_total 18663
telemt_me_route_drop_no_conn_total 306930
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601079
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 17755
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17378
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 574025
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 10015445460 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 305499529404 (284.52 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 62
```