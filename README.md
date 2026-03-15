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

# Server Metrics 2026-03-15 13:52:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 56255.2 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251228
telemt_connections_bad_total 2313
telemt_handshake_timeouts_total 5655
telemt_upstream_connect_attempt_total 14183
telemt_upstream_connect_success_total 14108
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 14663
telemt_me_reconnect_success_total 11285
telemt_me_reader_eof_total 12044
telemt_me_idle_close_by_peer_total 12044
telemt_me_route_drop_no_conn_total 435091
telemt_me_route_drop_channel_closed_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294850
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1681
telemt_desync_full_logged_total 663
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 723
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11507
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11254
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 233953
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 5183173812 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 206566289552 (192.38 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 56262.5 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92323
telemt_connections_bad_total 2746
telemt_handshake_timeouts_total 8801
telemt_upstream_connect_attempt_total 15463
telemt_upstream_connect_success_total 15463
telemt_upstream_connect_attempts_per_request{bucket="1"} 15463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 14958
telemt_me_reconnect_success_total 12612
telemt_me_reader_eof_total 13498
telemt_me_idle_close_by_peer_total 13498
telemt_me_route_drop_no_conn_total 39271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77962
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12826
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12596
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 77955
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 1531951656 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 37664813948 (35.08 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 56255.1 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94554
telemt_connections_bad_total 1611
telemt_handshake_timeouts_total 2741
telemt_upstream_connect_attempt_total 16673
telemt_upstream_connect_success_total 16665
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 16673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 17051
telemt_me_reconnect_success_total 13810
telemt_me_reader_eof_total 14761
telemt_me_idle_close_by_peer_total 14761
telemt_me_route_drop_no_conn_total 36974
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86203
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14043
telemt_me_refill_failed_total 99
telemt_me_writer_restored_same_endpoint_total 13802
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 86109
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 10034507200 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 51930164292 (48.36 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 56254.7 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131000
telemt_connections_bad_total 552
telemt_handshake_timeouts_total 855
telemt_upstream_connect_attempt_total 13349
telemt_upstream_connect_success_total 13346
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10585
telemt_me_reconnect_success_total 10522
telemt_me_reader_eof_total 11200
telemt_me_idle_close_by_peer_total 11200
telemt_me_route_drop_no_conn_total 50846
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119446
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 417
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10641
telemt_me_writer_restored_same_endpoint_total 10511
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 119362
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 2252981552 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 60803789108 (56.63 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 31326.2 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75580
telemt_connections_bad_total 20902
telemt_handshake_timeouts_total 1402
telemt_upstream_connect_attempt_total 10016
telemt_upstream_connect_success_total 9951
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 10016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 102631
telemt_me_reconnect_success_total 8206
telemt_me_reader_eof_total 8560
telemt_me_idle_close_by_peer_total 8560
telemt_me_route_drop_no_conn_total 25418
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51601
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 8214
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8102
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 51738
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 784352969 (748.02 MB)
telemt_user_octets_to_client{user="hello"} 20719703723 (19.30 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 56254.2 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333309
telemt_connections_bad_total 47913
telemt_handshake_timeouts_total 2619
telemt_upstream_connect_attempt_total 11990
telemt_upstream_connect_success_total 11919
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 9149
telemt_me_reconnect_success_total 9085
telemt_me_reader_eof_total 9659
telemt_me_idle_close_by_peer_total 9659
telemt_me_route_drop_no_conn_total 152730
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273326
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 279
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9171
telemt_me_writer_restored_same_endpoint_total 9058
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 271187
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 6567367132 (6.12 GB)
telemt_user_octets_to_client{user="hello"} 133149464888 (124.01 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 75
```