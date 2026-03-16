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

# Server Metrics 2026-03-16 05:31:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 112606.2 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484340
telemt_connections_bad_total 5502
telemt_handshake_timeouts_total 17511
telemt_upstream_connect_attempt_total 26790
telemt_upstream_connect_success_total 26668
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 26790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24501
telemt_me_reconnect_success_total 21074
telemt_me_reader_eof_total 22542
telemt_me_idle_close_by_peer_total 22542
telemt_me_route_drop_no_conn_total 508845
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502439
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2455
telemt_desync_full_logged_total 978
telemt_desync_suppressed_total 1477
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 996
telemt_pool_swap_total 109
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21409
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21040
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 441286
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 8858128644 (8.25 GB)
telemt_user_octets_to_client{user="hello"} 302712852732 (281.92 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 112612.6 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195146
telemt_connections_bad_total 3001
telemt_handshake_timeouts_total 14821
telemt_upstream_connect_attempt_total 30469
telemt_upstream_connect_success_total 30394
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 30469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 31297
telemt_me_reconnect_success_total 24385
telemt_me_reader_eof_total 26137
telemt_me_idle_close_by_peer_total 26136
telemt_me_route_drop_no_conn_total 98532
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170224
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 24939
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 24369
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 169767
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 3788114437 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 88551027732 (82.47 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 112605.1 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216351
telemt_connections_bad_total 3839
telemt_handshake_timeouts_total 4169
telemt_upstream_connect_attempt_total 31618
telemt_upstream_connect_success_total 31610
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 33346
telemt_me_reconnect_success_total 25952
telemt_me_reader_eof_total 27952
telemt_me_idle_close_by_peer_total 27951
telemt_me_route_drop_no_conn_total 76717
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171144
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 26438
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 25944
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 170868
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 16578786149 (15.44 GB)
telemt_user_octets_to_client{user="hello"} 105395504232 (98.16 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 112604.7 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286224
telemt_connections_bad_total 1266
telemt_handshake_timeouts_total 2635
telemt_upstream_connect_attempt_total 26256
telemt_upstream_connect_success_total 26230
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 26256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 20758
telemt_me_reconnect_success_total 20633
telemt_me_reader_eof_total 22036
telemt_me_idle_close_by_peer_total 22035
telemt_me_route_drop_no_conn_total 104467
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262914
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 581
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 20888
telemt_me_writer_restored_same_endpoint_total 20622
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 262803
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 4396147708 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 116544753160 (108.54 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 87676.2 (24h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192689
telemt_connections_bad_total 34411
telemt_handshake_timeouts_total 3439
telemt_upstream_connect_attempt_total 25136
telemt_upstream_connect_success_total 24999
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 25136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 114948
telemt_me_reconnect_success_total 20470
telemt_me_reader_eof_total 21745
telemt_me_idle_close_by_peer_total 21745
telemt_me_route_drop_no_conn_total 60765
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150033
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 20634
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 20366
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 149667
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 2043756569 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 66481838231 (61.92 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 112604.0 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723551
telemt_connections_bad_total 63264
telemt_handshake_timeouts_total 5444
telemt_upstream_connect_attempt_total 23865
telemt_upstream_connect_success_total 23737
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 23865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19449
telemt_me_reconnect_success_total 18113
telemt_me_reader_eof_total 19339
telemt_me_idle_close_by_peer_total 19339
telemt_me_route_drop_no_conn_total 611362
telemt_me_route_drop_channel_closed_total 97
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735993
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
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18364
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18086
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 594660
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 13539321832 (12.61 GB)
telemt_user_octets_to_client{user="hello"} 366258228744 (341.10 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 58
```