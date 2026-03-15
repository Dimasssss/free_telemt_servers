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

# Server Metrics 2026-03-15 19:18:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 75854.4 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356533
telemt_connections_bad_total 4333
telemt_handshake_timeouts_total 13123
telemt_upstream_connect_attempt_total 18294
telemt_upstream_connect_success_total 18201
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 18294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17803
telemt_me_reconnect_success_total 14404
telemt_me_reader_eof_total 15353
telemt_me_idle_close_by_peer_total 15353
telemt_me_route_drop_no_conn_total 471986
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386595
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1927
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 1170
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 749
telemt_desync_frames_bucket_total{bucket="gt_10"} 812
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14666
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14370
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 325654
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 6925004456 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 250501225760 (233.30 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 75860.9 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144773
telemt_connections_bad_total 2844
telemt_handshake_timeouts_total 12828
telemt_upstream_connect_attempt_total 20435
telemt_upstream_connect_success_total 20424
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 20435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 597
telemt_me_reconnect_attempts_total 18959
telemt_me_reconnect_success_total 16559
telemt_me_reader_eof_total 17689
telemt_me_idle_close_by_peer_total 17688
telemt_me_route_drop_no_conn_total 60904
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123321
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
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16870
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16543
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 123301
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 2350368920 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 60976644092 (56.79 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 75853.4 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147284
telemt_connections_bad_total 1706
telemt_handshake_timeouts_total 3350
telemt_upstream_connect_attempt_total 21968
telemt_upstream_connect_success_total 21960
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25469
telemt_me_reconnect_success_total 18106
telemt_me_reader_eof_total 19441
telemt_me_idle_close_by_peer_total 19441
telemt_me_route_drop_no_conn_total 57670
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130048
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 18515
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18098
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 409
telemt_user_connections_total{user="hello"} 129939
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 10814880856 (10.07 GB)
telemt_user_octets_to_client{user="hello"} 70947828848 (66.08 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 75853.0 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207974
telemt_connections_bad_total 1115
telemt_handshake_timeouts_total 1476
telemt_upstream_connect_attempt_total 17854
telemt_upstream_connect_success_total 17840
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14131
telemt_me_reconnect_success_total 14045
telemt_me_reader_eof_total 14956
telemt_me_idle_close_by_peer_total 14956
telemt_me_route_drop_no_conn_total 77131
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191717
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 686
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14212
telemt_me_writer_restored_same_endpoint_total 14034
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 191635
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 3622392736 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 88359691364 (82.29 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 50924.5 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124873
telemt_connections_bad_total 25101
telemt_handshake_timeouts_total 2473
telemt_upstream_connect_attempt_total 15061
telemt_upstream_connect_success_total 14970
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106692
telemt_me_reconnect_success_total 12243
telemt_me_reader_eof_total 12864
telemt_me_idle_close_by_peer_total 12864
telemt_me_route_drop_no_conn_total 43024
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93852
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 292
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 12323
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12139
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 93982
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 1540756445 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 35686100267 (33.24 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 75852.5 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512537
telemt_connections_bad_total 58009
telemt_handshake_timeouts_total 4204
telemt_upstream_connect_attempt_total 16230
telemt_upstream_connect_success_total 16137
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13621
telemt_me_reconnect_success_total 12313
telemt_me_reader_eof_total 13087
telemt_me_idle_close_by_peer_total 13087
telemt_me_route_drop_no_conn_total 327639
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473665
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12485
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12286
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 431432
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 11094671048 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 238065173016 (221.72 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 75
```