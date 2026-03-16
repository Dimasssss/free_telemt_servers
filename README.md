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

# Server Metrics 2026-03-16 02:42:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 102495.2 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441430
telemt_connections_bad_total 5364
telemt_handshake_timeouts_total 14672
telemt_upstream_connect_attempt_total 24477
telemt_upstream_connect_success_total 24363
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 24477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 22714
telemt_me_reconnect_success_total 19294
telemt_me_reader_eof_total 20628
telemt_me_idle_close_by_peer_total 20628
telemt_me_route_drop_no_conn_total 498185
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466103
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2279
telemt_desync_full_logged_total 912
telemt_desync_suppressed_total 1367
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 19612
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 19260
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 404961
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 8437256492 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 289239679456 (269.38 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 102501.5 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180279
telemt_connections_bad_total 2963
telemt_handshake_timeouts_total 14615
telemt_upstream_connect_attempt_total 27927
telemt_upstream_connect_success_total 27852
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 27927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 29273
telemt_me_reconnect_success_total 22369
telemt_me_reader_eof_total 23951
telemt_me_idle_close_by_peer_total 23950
telemt_me_route_drop_no_conn_total 91054
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156156
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 22898
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 22353
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 155702
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 3445645481 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 80889264312 (75.33 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 102494.1 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197436
telemt_connections_bad_total 2561
telemt_handshake_timeouts_total 3828
telemt_upstream_connect_attempt_total 29047
telemt_upstream_connect_success_total 29039
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 31296
telemt_me_reconnect_success_total 23911
telemt_me_reader_eof_total 25736
telemt_me_idle_close_by_peer_total 25735
telemt_me_route_drop_no_conn_total 70433
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158889
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
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24373
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 23903
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 158658
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 16414303044 (15.29 GB)
telemt_user_octets_to_client{user="hello"} 101227742452 (94.28 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 102493.8 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263114
telemt_connections_bad_total 1220
telemt_handshake_timeouts_total 1682
telemt_upstream_connect_attempt_total 24009
telemt_upstream_connect_success_total 23988
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 24009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 19028
telemt_me_reconnect_success_total 18916
telemt_me_reader_eof_total 20179
telemt_me_idle_close_by_peer_total 20178
telemt_me_route_drop_no_conn_total 96280
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243226
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 879
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 380
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 19145
telemt_me_writer_restored_same_endpoint_total 18905
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 243108
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 4162507964 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 110298886700 (102.72 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 77565.3 (21h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173207
telemt_connections_bad_total 30697
telemt_handshake_timeouts_total 3032
telemt_upstream_connect_attempt_total 22171
telemt_upstream_connect_success_total 22048
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 112476
telemt_me_reconnect_success_total 18007
telemt_me_reader_eof_total 19110
telemt_me_idle_close_by_peer_total 19110
telemt_me_route_drop_no_conn_total 54160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134749
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 18148
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 17903
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 134867
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 1886262061 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 45578138099 (42.45 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 102493.0 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664268
telemt_connections_bad_total 58727
telemt_handshake_timeouts_total 4997
telemt_upstream_connect_attempt_total 21717
telemt_upstream_connect_success_total 21601
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 21717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11273
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 17831
telemt_me_reconnect_success_total 16503
telemt_me_reader_eof_total 17604
telemt_me_idle_close_by_peer_total 17604
telemt_me_route_drop_no_conn_total 589887
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692570
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 16736
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 16476
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 551248
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 12907139960 (12.02 GB)
telemt_user_octets_to_client{user="hello"} 337340945544 (314.17 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 43
```