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

# Server Metrics 2026-03-13 17:48:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 123294.8 (34h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520511
telemt_connections_bad_total 8140
telemt_handshake_timeouts_total 12018
telemt_upstream_connect_attempt_total 30921
telemt_upstream_connect_success_total 30770
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 30921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3440
telemt_me_reconnect_attempts_total 29257
telemt_me_reconnect_success_total 24617
telemt_me_reader_eof_total 26284
telemt_me_idle_close_by_peer_total 26283
telemt_me_route_drop_no_conn_total 169244
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452421
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 957
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 25033
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24601
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 451990
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 8347893344 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 212645369564 (198.04 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 123187.8 (34h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256367
telemt_connections_bad_total 1951
telemt_handshake_timeouts_total 1821
telemt_upstream_connect_attempt_total 110115
telemt_upstream_connect_success_total 109277
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 110115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1568
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 1516
telemt_me_reconnect_attempts_total 125952
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29909
telemt_me_idle_close_by_peer_total 29909
telemt_me_route_drop_no_conn_total 82474
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165848
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 30
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
telemt_me_writer_removed_unexpected_total 29379
telemt_me_refill_failed_total 3118
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3346
telemt_user_connections_total{user="hello"} 242741
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 2532110613 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 74821249399 (69.68 GB)
telemt_user_msgs_from_client{user="hello"} 1209360
telemt_user_msgs_to_client{user="hello"} 7067567
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 123151.8 (34h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302950
telemt_connections_bad_total 2515
telemt_handshake_timeouts_total 17269
telemt_upstream_connect_attempt_total 32846
telemt_upstream_connect_success_total 32842
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2636
telemt_me_reconnect_attempts_total 27885
telemt_me_reconnect_success_total 26655
telemt_me_reader_eof_total 28578
telemt_me_idle_close_by_peer_total 28578
telemt_me_route_drop_no_conn_total 108217
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272509
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 26954
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26635
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 272418
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 10168975960 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 112372949348 (104.66 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 123127.0 (34h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409275
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3866
telemt_upstream_connect_attempt_total 60118
telemt_upstream_connect_success_total 49871
telemt_upstream_connect_fail_total 10247
telemt_upstream_connect_attempts_per_request{bucket="1"} 60118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10247
telemt_me_keepalive_timeout_total 4656
telemt_me_reconnect_attempts_total 114354
telemt_me_reconnect_success_total 24699
telemt_me_reader_eof_total 28200
telemt_me_idle_close_by_peer_total 28193
telemt_me_route_drop_no_conn_total 141095
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341420
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1353
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 950
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 27811
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24689
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3112
telemt_user_connections_total{user="hello"} 360310
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 8365167043 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 129073403684 (120.21 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 73298.5 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120158
telemt_connections_bad_total 15201
telemt_handshake_timeouts_total 1394
telemt_upstream_connect_attempt_total 28964
telemt_upstream_connect_success_total 28696
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 28964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 1168
telemt_me_reconnect_attempts_total 33505
telemt_me_reconnect_success_total 20118
telemt_me_reader_eof_total 21572
telemt_me_idle_close_by_peer_total 21572
telemt_me_route_drop_no_conn_total 37562
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94791
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 439
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 20719
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20100
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 99688
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 1191953829 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 32680261111 (30.44 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 123083.8 (34h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752238
telemt_connections_bad_total 24742
telemt_handshake_timeouts_total 24437
telemt_upstream_connect_attempt_total 25624
telemt_upstream_connect_success_total 25489
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 25624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2969
telemt_me_reconnect_attempts_total 24025
telemt_me_reconnect_success_total 19382
telemt_me_reader_eof_total 20800
telemt_me_idle_close_by_peer_total 20797
telemt_me_route_drop_no_conn_total 356220
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705669
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 19781
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19375
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 678553
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 11927259488 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 339256967364 (315.96 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 78
```