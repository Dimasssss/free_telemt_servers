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

# Server Metrics 2026-03-12 14:25:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24721.0 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130654
telemt_connections_bad_total 1373
telemt_handshake_timeouts_total 4500
telemt_upstream_connect_attempt_total 6071
telemt_upstream_connect_success_total 6047
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 4793
telemt_me_reconnect_success_total 4761
telemt_me_reader_eof_total 5006
telemt_me_idle_close_by_peer_total 5005
telemt_me_route_drop_no_conn_total 37157
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114340
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 549
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4803
telemt_me_writer_restored_same_endpoint_total 4745
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 114302
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 1918259612 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 43135518856 (40.17 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24615.0 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53933
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 362
telemt_upstream_connect_attempt_total 7364
telemt_upstream_connect_success_total 7193
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 7364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 21763
telemt_me_reconnect_success_total 5929
telemt_me_reader_eof_total 6540
telemt_me_idle_close_by_peer_total 6540
telemt_me_route_drop_no_conn_total 24038
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51479
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6461
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5914
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 532
telemt_user_connections_total{user="hello"} 51473
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 593299016 (565.81 MB)
telemt_user_octets_to_client{user="hello"} 14842659476 (13.82 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24577.5 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74367
telemt_connections_bad_total 1417
telemt_handshake_timeouts_total 1122
telemt_upstream_connect_attempt_total 6635
telemt_upstream_connect_success_total 6635
telemt_upstream_connect_attempts_per_request{bucket="1"} 6635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 5377
telemt_me_reconnect_success_total 5334
telemt_me_reader_eof_total 5636
telemt_me_idle_close_by_peer_total 5636
telemt_me_route_drop_no_conn_total 25992
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68646
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5372
telemt_me_writer_restored_same_endpoint_total 5314
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 68625
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 1908966600 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 39527154096 (36.81 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24553.1 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94286
telemt_connections_bad_total 1977
telemt_handshake_timeouts_total 713
telemt_upstream_connect_attempt_total 6437
telemt_upstream_connect_success_total 6268
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 6437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 19439
telemt_me_reconnect_success_total 4987
telemt_me_reader_eof_total 5571
telemt_me_idle_close_by_peer_total 5571
telemt_me_route_drop_no_conn_total 34934
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86177
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 276
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 184
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5496
telemt_me_refill_failed_total 450
telemt_me_writer_restored_same_endpoint_total 4979
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 509
telemt_user_connections_total{user="hello"} 86060
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 1437072988 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 35800894412 (33.34 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24522.6 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55205
telemt_connections_bad_total 4684
telemt_handshake_timeouts_total 707
telemt_upstream_connect_attempt_total 20828
telemt_upstream_connect_success_total 20519
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 20828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 32671
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4586
telemt_me_idle_close_by_peer_total 4586
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12235
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32950
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 443
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4611
telemt_me_refill_failed_total 907
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 927
telemt_user_connections_total{user="hello"} 48506
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 403124926 (384.45 MB)
telemt_user_octets_to_client{user="hello"} 12125325344 (11.29 GB)
telemt_user_msgs_from_client{user="hello"} 224150
telemt_user_msgs_to_client{user="hello"} 641874
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24509.8 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148686
telemt_connections_bad_total 781
telemt_handshake_timeouts_total 1124
telemt_upstream_connect_attempt_total 5062
telemt_upstream_connect_success_total 5035
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3797
telemt_me_reconnect_success_total 3767
telemt_me_reader_eof_total 3972
telemt_me_idle_close_by_peer_total 3972
telemt_me_route_drop_no_conn_total 58493
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142185
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 230
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3811
telemt_me_writer_restored_same_endpoint_total 3760
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 142151
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 2884434832 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 59556143996 (55.47 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 61
```