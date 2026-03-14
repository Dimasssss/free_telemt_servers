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

# Server Metrics 2026-03-14 21:44:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 30512.7 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144679
telemt_connections_bad_total 16396
telemt_handshake_timeouts_total 1541
telemt_upstream_connect_attempt_total 6879
telemt_upstream_connect_success_total 6877
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 5371
telemt_me_reconnect_success_total 5332
telemt_me_reader_eof_total 5664
telemt_me_idle_close_by_peer_total 5664
telemt_me_route_drop_no_conn_total 52469
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120223
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 579
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5418
telemt_me_writer_restored_same_endpoint_total 5314
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 120143
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 2553980736 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 72949320152 (67.94 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 30510.8 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59957
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 998
telemt_upstream_connect_attempt_total 7917
telemt_upstream_connect_success_total 7867
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 7917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 8903
telemt_me_reconnect_success_total 6320
telemt_me_reader_eof_total 6726
telemt_me_idle_close_by_peer_total 6726
telemt_me_route_drop_no_conn_total 32417
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55967
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6485
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6315
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 55888
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1388985196 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 25604764500 (23.85 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 30515.5 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67981
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1912
telemt_upstream_connect_attempt_total 9992
telemt_upstream_connect_success_total 9890
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 9992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 270
telemt_me_reconnect_attempts_total 105893
telemt_me_reconnect_success_total 8028
telemt_me_reader_eof_total 8577
telemt_me_idle_close_by_peer_total 8577
telemt_me_route_drop_no_conn_total 25244
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62258
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 8313
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7982
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 62321
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 3960774865 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 49450347878 (46.05 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 30520.2 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85645
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 7419
telemt_upstream_connect_success_total 7375
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 7419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 5695
telemt_me_reconnect_success_total 5666
telemt_me_reader_eof_total 5976
telemt_me_idle_close_by_peer_total 5976
telemt_me_route_drop_no_conn_total 37295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81190
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 663
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5728
telemt_me_writer_restored_same_endpoint_total 5664
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 81234
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 1343372340 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 29264641258 (27.25 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 30513.4 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64858
telemt_connections_bad_total 5948
telemt_handshake_timeouts_total 3388
telemt_upstream_connect_attempt_total 7411
telemt_upstream_connect_success_total 7326
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 7411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 230
telemt_me_reconnect_attempts_total 12316
telemt_me_reconnect_success_total 5777
telemt_me_reader_eof_total 6253
telemt_me_idle_close_by_peer_total 6253
telemt_me_route_drop_no_conn_total 20811
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52279
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 270
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6036
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5773
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 52265
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 1413178220 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 32085463588 (29.88 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 30512.9 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218561
telemt_connections_bad_total 7716
telemt_handshake_timeouts_total 2712
telemt_upstream_connect_attempt_total 6057
telemt_upstream_connect_success_total 5948
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 6057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 9413
telemt_me_reconnect_success_total 4404
telemt_me_reader_eof_total 4766
telemt_me_idle_close_by_peer_total 4766
telemt_me_route_drop_no_conn_total 121724
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201780
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4616
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4400
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 198264
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 6075623808 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 108999019928 (101.51 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 42
```