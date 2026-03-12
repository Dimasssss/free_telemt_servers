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

# Server Metrics 2026-03-12 22:31:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 53862.1 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245266
telemt_connections_bad_total 2688
telemt_handshake_timeouts_total 5242
telemt_upstream_connect_attempt_total 13498
telemt_upstream_connect_success_total 13436
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 13497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1470
telemt_me_reconnect_attempts_total 14182
telemt_me_reconnect_success_total 10713
telemt_me_reader_eof_total 11407
telemt_me_idle_close_by_peer_total 11406
telemt_me_route_drop_no_conn_total 75429
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201812
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 433
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10943
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 10697
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 201579
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 3775139664 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 98804902972 (92.02 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 53755.4 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109819
telemt_connections_bad_total 565
telemt_handshake_timeouts_total 815
telemt_upstream_connect_attempt_total 31849
telemt_upstream_connect_success_total 31497
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 31849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 499
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_keepalive_timeout_total 389
telemt_me_reconnect_attempts_total 52941
telemt_me_reconnect_success_total 12292
telemt_me_reader_eof_total 13832
telemt_me_idle_close_by_peer_total 13832
telemt_me_route_drop_no_conn_total 40094
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87974
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 13650
telemt_me_refill_failed_total 1269
telemt_me_writer_restored_same_endpoint_total 12277
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1358
telemt_user_connections_total{user="hello"} 104475
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 1172212820 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 33551387351 (31.25 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 53718.8 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136117
telemt_connections_bad_total 1582
telemt_handshake_timeouts_total 2218
telemt_upstream_connect_attempt_total 14794
telemt_upstream_connect_success_total 14793
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 13189
telemt_me_reconnect_success_total 12046
telemt_me_reader_eof_total 12842
telemt_me_idle_close_by_peer_total 12842
telemt_me_route_drop_no_conn_total 51156
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127171
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 12196
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 12026
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 127138
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 2571354716 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 60022368160 (55.90 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 53694.6 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198779
telemt_connections_bad_total 13239
telemt_handshake_timeouts_total 1370
telemt_upstream_connect_attempt_total 26074
telemt_upstream_connect_success_total 16384
telemt_upstream_connect_fail_total 9690
telemt_upstream_connect_attempts_per_request{bucket="1"} 26074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9690
telemt_me_keepalive_timeout_total 2475
telemt_me_reconnect_attempts_total 43055
telemt_me_reconnect_success_total 10810
telemt_me_reader_eof_total 12189
telemt_me_idle_close_by_peer_total 12182
telemt_me_route_drop_no_conn_total 69647
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162912
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 11985
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 10800
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1175
telemt_user_connections_total{user="hello"} 165666
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 2969076618 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 67815514001 (63.16 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3866.1 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3828
telemt_connections_bad_total 695
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1100
telemt_upstream_connect_success_total 1090
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 850
telemt_me_reconnect_success_total 849
telemt_me_reader_eof_total 891
telemt_me_idle_close_by_peer_total 891
telemt_me_route_drop_no_conn_total 1030
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2979
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 851
telemt_me_writer_restored_same_endpoint_total 833
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 2979
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 7917416 (7.55 MB)
telemt_user_octets_to_client{user="hello"} 1117421348 (1.04 GB)
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 53651.0 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322553
telemt_connections_bad_total 5067
telemt_handshake_timeouts_total 2488
telemt_upstream_connect_attempt_total 11217
telemt_upstream_connect_success_total 11156
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 503
telemt_me_reconnect_attempts_total 12075
telemt_me_reconnect_success_total 8466
telemt_me_reader_eof_total 9045
telemt_me_idle_close_by_peer_total 9044
telemt_me_route_drop_no_conn_total 146205
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317146
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8682
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8459
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 305448
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 5402298824 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 160015420504 (149.03 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 21
```