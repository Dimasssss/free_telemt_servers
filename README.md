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

# Server Metrics 2026-03-16 17:26:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 13711.8 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141902
telemt_connections_bad_total 619
telemt_handshake_timeouts_total 3856
telemt_upstream_connect_attempt_total 2966
telemt_upstream_connect_success_total 2954
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3367
telemt_me_reconnect_success_total 2196
telemt_me_reader_eof_total 2283
telemt_me_idle_close_by_peer_total 2282
telemt_me_route_drop_no_conn_total 42864
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132755
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 688
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2246
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2194
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 132675
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 2426701660 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 77229963856 (71.93 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 8490.2 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60687
telemt_connections_bad_total 517
telemt_handshake_timeouts_total 2911
telemt_upstream_connect_attempt_total 1844
telemt_upstream_connect_success_total 1832
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 4855
telemt_me_reconnect_success_total 1348
telemt_me_reader_eof_total 1472
telemt_me_idle_close_by_peer_total 1472
telemt_me_route_drop_no_conn_total 36261
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55098
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1482
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1343
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 55050
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 700006808 (667.58 MB)
telemt_user_octets_to_client{user="hello"} 16506197892 (15.37 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 13824.7 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55738
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 856
telemt_upstream_connect_attempt_total 4064
telemt_upstream_connect_success_total 4020
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 4064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 40044
telemt_me_reconnect_success_total 2280
telemt_me_reader_eof_total 2570
telemt_me_idle_close_by_peer_total 2570
telemt_me_route_drop_no_conn_total 19607
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51050
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2576
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 2236
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 51991
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 652549130 (622.32 MB)
telemt_user_octets_to_client{user="hello"} 14502765946 (13.51 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 13960.8 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110356
telemt_connections_bad_total 218
telemt_handshake_timeouts_total 1731
telemt_upstream_connect_attempt_total 3060
telemt_upstream_connect_success_total 3035
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 8602
telemt_me_reconnect_success_total 2247
telemt_me_reader_eof_total 2484
telemt_me_idle_close_by_peer_total 2483
telemt_me_route_drop_no_conn_total 41012
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104490
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 588
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 427
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2474
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2243
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 104465
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 1429743700 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 26911970924 (25.06 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 11421.3 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64337
telemt_connections_bad_total 20014
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 2871
telemt_upstream_connect_success_total 2833
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 2871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 3875
telemt_me_reconnect_success_total 2221
telemt_me_reader_eof_total 2329
telemt_me_idle_close_by_peer_total 2329
telemt_me_route_drop_no_conn_total 48965
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60424
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2310
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2221
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 41477
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 1993714212 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 30338859664 (28.26 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 13529.3 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159104
telemt_connections_bad_total 1987
telemt_handshake_timeouts_total 3334
telemt_upstream_connect_attempt_total 2844
telemt_upstream_connect_success_total 2844
telemt_upstream_connect_attempts_per_request{bucket="1"} 2844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7156
telemt_me_reconnect_success_total 2131
telemt_me_reader_eof_total 2324
telemt_me_idle_close_by_peer_total 2323
telemt_me_route_drop_no_conn_total 71638
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147268
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2305
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2125
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 146985
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 3000987676 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 54790016028 (51.03 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 105
```