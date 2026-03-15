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

# Server Metrics 2026-03-15 09:01:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 38802.2 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146522
telemt_connections_bad_total 1142
telemt_handshake_timeouts_total 3731
telemt_upstream_connect_attempt_total 9543
telemt_upstream_connect_success_total 9488
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 7568
telemt_me_reconnect_success_total 7539
telemt_me_reader_eof_total 8033
telemt_me_idle_close_by_peer_total 8033
telemt_me_route_drop_no_conn_total 317939
telemt_me_route_drop_channel_closed_total 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185089
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1075
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 631
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7608
telemt_me_writer_restored_same_endpoint_total 7508
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 136275
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 1840606744 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 140018098964 (130.40 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 38809.1 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45001
telemt_connections_bad_total 295
telemt_handshake_timeouts_total 2444
telemt_upstream_connect_attempt_total 10598
telemt_upstream_connect_success_total 10598
telemt_upstream_connect_attempts_per_request{bucket="1"} 10598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 10933
telemt_me_reconnect_success_total 8623
telemt_me_reader_eof_total 9272
telemt_me_idle_close_by_peer_total 9272
telemt_me_route_drop_no_conn_total 22505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40693
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8783
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 8607
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 40694
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 897365788 (855.79 MB)
telemt_user_octets_to_client{user="hello"} 14725500744 (13.71 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 38801.6 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54428
telemt_connections_bad_total 496
telemt_handshake_timeouts_total 1927
telemt_upstream_connect_attempt_total 10293
telemt_upstream_connect_success_total 10292
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8367
telemt_me_reconnect_success_total 8325
telemt_me_reader_eof_total 8996
telemt_me_idle_close_by_peer_total 8996
telemt_me_route_drop_no_conn_total 19405
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49708
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8405
telemt_me_writer_restored_same_endpoint_total 8321
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 49639
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 9063479960 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 32591108384 (30.35 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 38801.5 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67393
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 414
telemt_upstream_connect_attempt_total 9290
telemt_upstream_connect_success_total 9289
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7367
telemt_me_reconnect_success_total 7336
telemt_me_reader_eof_total 7826
telemt_me_idle_close_by_peer_total 7826
telemt_me_route_drop_no_conn_total 28801
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61220
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 131
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7411
telemt_me_writer_restored_same_endpoint_total 7325
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 61156
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 1211563760 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 37907889600 (35.30 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 13872.9 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22357
telemt_connections_bad_total 2641
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 4845
telemt_upstream_connect_success_total 4801
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 4845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 98319
telemt_me_reconnect_success_total 3915
telemt_me_reader_eof_total 4031
telemt_me_idle_close_by_peer_total 4031
telemt_me_route_drop_no_conn_total 7002
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18757
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3873
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3811
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 18897
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 171443597 (163.50 MB)
telemt_user_octets_to_client{user="hello"} 10542289675 (9.82 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 38800.8 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173305
telemt_connections_bad_total 21709
telemt_handshake_timeouts_total 998
telemt_upstream_connect_attempt_total 8357
telemt_upstream_connect_success_total 8307
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 8357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 6380
telemt_me_reconnect_success_total 6349
telemt_me_reader_eof_total 6768
telemt_me_idle_close_by_peer_total 6768
telemt_me_route_drop_no_conn_total 82710
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145948
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6386
telemt_me_writer_restored_same_endpoint_total 6322
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 144490
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 3993697540 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 75487197868 (70.30 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 67
```