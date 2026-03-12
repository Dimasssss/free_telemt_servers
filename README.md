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

# Server Metrics 2026-03-12 15:11:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27485.8 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146126
telemt_connections_bad_total 1661
telemt_handshake_timeouts_total 4585
telemt_upstream_connect_attempt_total 6687
telemt_upstream_connect_success_total 6661
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 276
telemt_me_reconnect_attempts_total 5276
telemt_me_reconnect_success_total 5240
telemt_me_reader_eof_total 5512
telemt_me_idle_close_by_peer_total 5511
telemt_me_route_drop_no_conn_total 42211
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126895
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 583
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5286
telemt_me_writer_restored_same_endpoint_total 5224
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 126857
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 2139059204 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 46999980724 (43.77 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27379.5 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61353
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 390
telemt_upstream_connect_attempt_total 8427
telemt_upstream_connect_success_total 8241
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 8427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 23763
telemt_me_reconnect_success_total 6839
telemt_me_reader_eof_total 7516
telemt_me_idle_close_by_peer_total 7516
telemt_me_route_drop_no_conn_total 27149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58526
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 7413
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 6824
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 58517
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 643234444 (613.44 MB)
telemt_user_octets_to_client{user="hello"} 16374146880 (15.25 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27342.4 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83457
telemt_connections_bad_total 1432
telemt_handshake_timeouts_total 1559
telemt_upstream_connect_attempt_total 7488
telemt_upstream_connect_success_total 7488
telemt_upstream_connect_attempts_per_request{bucket="1"} 7488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 6095
telemt_me_reconnect_success_total 6042
telemt_me_reader_eof_total 6375
telemt_me_idle_close_by_peer_total 6375
telemt_me_route_drop_no_conn_total 29963
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76988
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 6092
telemt_me_writer_restored_same_endpoint_total 6022
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 76962
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 2048508440 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 42236533028 (39.34 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27318.3 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111126
telemt_connections_bad_total 8291
telemt_handshake_timeouts_total 789
telemt_upstream_connect_attempt_total 6793
telemt_upstream_connect_success_total 6608
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 6793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 258
telemt_me_reconnect_attempts_total 23679
telemt_me_reconnect_success_total 5195
telemt_me_reader_eof_total 5908
telemt_me_idle_close_by_peer_total 5908
telemt_me_route_drop_no_conn_total 39369
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96126
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5833
telemt_me_refill_failed_total 576
telemt_me_writer_restored_same_endpoint_total 5187
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 96009
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 1799413228 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 39398646180 (36.69 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27287.7 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63647
telemt_connections_bad_total 5287
telemt_handshake_timeouts_total 1061
telemt_upstream_connect_attempt_total 27778
telemt_upstream_connect_success_total 27439
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 27778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 36911
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4719
telemt_me_idle_close_by_peer_total 4719
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12528
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33443
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4745
telemt_me_refill_failed_total 1041
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1061
telemt_user_connections_total{user="hello"} 55785
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 473550130 (451.61 MB)
telemt_user_octets_to_client{user="hello"} 16982392507 (15.82 GB)
telemt_user_msgs_from_client{user="hello"} 346942
telemt_user_msgs_to_client{user="hello"} 1496956
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27275.0 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168892
telemt_connections_bad_total 897
telemt_handshake_timeouts_total 1321
telemt_upstream_connect_attempt_total 5696
telemt_upstream_connect_success_total 5667
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 5696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 4296
telemt_me_reconnect_success_total 4264
telemt_me_reader_eof_total 4477
telemt_me_idle_close_by_peer_total 4477
telemt_me_route_drop_no_conn_total 65644
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161535
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 242
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4312
telemt_me_writer_restored_same_endpoint_total 4257
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 161498
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 3278449564 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 74040855120 (68.96 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 47
```