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

# Server Metrics 2026-03-15 15:03:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 60543.8 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274944
telemt_connections_bad_total 2667
telemt_handshake_timeouts_total 8195
telemt_upstream_connect_attempt_total 15215
telemt_upstream_connect_success_total 15134
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 15215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15471
telemt_me_reconnect_success_total 12089
telemt_me_reader_eof_total 12876
telemt_me_idle_close_by_peer_total 12876
telemt_me_route_drop_no_conn_total 443654
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314095
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1733
telemt_desync_full_logged_total 692
telemt_desync_suppressed_total 1041
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 680
telemt_desync_frames_bucket_total{bucket="gt_10"} 741
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12321
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12055
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 253201
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 5609905676 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 215333366168 (200.54 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 60550.5 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102159
telemt_connections_bad_total 2795
telemt_handshake_timeouts_total 9630
telemt_upstream_connect_attempt_total 16741
telemt_upstream_connect_success_total 16741
telemt_upstream_connect_attempts_per_request{bucket="1"} 16741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16011
telemt_me_reconnect_success_total 13655
telemt_me_reader_eof_total 14598
telemt_me_idle_close_by_peer_total 14598
telemt_me_route_drop_no_conn_total 43245
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86616
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13888
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13639
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 86607
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 1697919308 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 42663402352 (39.73 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 60543.2 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111760
telemt_connections_bad_total 1658
telemt_handshake_timeouts_total 2816
telemt_upstream_connect_attempt_total 17858
telemt_upstream_connect_success_total 17850
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22097
telemt_me_reconnect_success_total 14753
telemt_me_reader_eof_total 15843
telemt_me_idle_close_by_peer_total 15843
telemt_me_route_drop_no_conn_total 42637
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96574
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15116
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 14745
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 96474
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 10278902440 (9.57 GB)
telemt_user_octets_to_client{user="hello"} 55659228668 (51.84 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 60542.5 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147479
telemt_connections_bad_total 799
telemt_handshake_timeouts_total 933
telemt_upstream_connect_attempt_total 14559
telemt_upstream_connect_success_total 14555
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11579
telemt_me_reconnect_success_total 11509
telemt_me_reader_eof_total 12251
telemt_me_idle_close_by_peer_total 12251
telemt_me_route_drop_no_conn_total 57321
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 11643
telemt_me_writer_restored_same_endpoint_total 11498
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 134996
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2500995596 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 65400249888 (60.91 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 35614.1 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85880
telemt_connections_bad_total 21686
telemt_handshake_timeouts_total 1586
telemt_upstream_connect_attempt_total 11166
telemt_upstream_connect_success_total 11098
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103558
telemt_me_reconnect_success_total 9127
telemt_me_reader_eof_total 9546
telemt_me_idle_close_by_peer_total 9546
telemt_me_route_drop_no_conn_total 29409
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60645
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 9153
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9023
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 60781
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 870296213 (829.98 MB)
telemt_user_octets_to_client{user="hello"} 24260004251 (22.59 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 60542.4 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369927
telemt_connections_bad_total 49433
telemt_handshake_timeouts_total 3084
telemt_upstream_connect_attempt_total 12968
telemt_upstream_connect_success_total 12890
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 12968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11111
telemt_me_reconnect_success_total 9819
telemt_me_reader_eof_total 10460
telemt_me_idle_close_by_peer_total 10460
telemt_me_route_drop_no_conn_total 173970
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306692
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 9954
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9792
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 304239
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 7733743488 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 157686714188 (146.86 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 82
```