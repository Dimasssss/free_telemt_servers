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

# Server Metrics 2026-03-12 15:31:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28714.9 (7h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152527
telemt_connections_bad_total 1957
telemt_handshake_timeouts_total 4642
telemt_upstream_connect_attempt_total 6936
telemt_upstream_connect_success_total 6909
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 277
telemt_me_reconnect_attempts_total 5480
telemt_me_reconnect_success_total 5440
telemt_me_reader_eof_total 5727
telemt_me_idle_close_by_peer_total 5726
telemt_me_route_drop_no_conn_total 43951
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131699
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 596
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5489
telemt_me_writer_restored_same_endpoint_total 5424
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 131666
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 2213229136 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 49888892500 (46.46 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28608.1 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64198
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 447
telemt_upstream_connect_attempt_total 8990
telemt_upstream_connect_success_total 8799
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 8990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 24276
telemt_me_reconnect_success_total 7348
telemt_me_reader_eof_total 8034
telemt_me_idle_close_by_peer_total 8034
telemt_me_route_drop_no_conn_total 27893
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61129
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 7931
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 7333
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 61120
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 689012644 (657.09 MB)
telemt_user_octets_to_client{user="hello"} 17551813780 (16.35 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28571.9 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86974
telemt_connections_bad_total 1434
telemt_handshake_timeouts_total 1648
telemt_upstream_connect_attempt_total 7892
telemt_upstream_connect_success_total 7892
telemt_upstream_connect_attempts_per_request{bucket="1"} 7892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 6456
telemt_me_reconnect_success_total 6399
telemt_me_reader_eof_total 6767
telemt_me_idle_close_by_peer_total 6767
telemt_me_route_drop_no_conn_total 31826
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80262
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6451
telemt_me_writer_restored_same_endpoint_total 6379
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 80235
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 2083327060 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 43280174884 (40.31 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28547.3 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119946
telemt_connections_bad_total 13034
telemt_handshake_timeouts_total 831
telemt_upstream_connect_attempt_total 6906
telemt_upstream_connect_success_total 6711
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 6906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 300
telemt_me_reconnect_attempts_total 25082
telemt_me_reconnect_success_total 5252
telemt_me_reader_eof_total 6006
telemt_me_idle_close_by_peer_total 6006
telemt_me_route_drop_no_conn_total 41118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99783
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 349
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5933
telemt_me_refill_failed_total 618
telemt_me_writer_restored_same_endpoint_total 5244
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 681
telemt_user_connections_total{user="hello"} 99664
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1934944324 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 41331764288 (38.49 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28516.8 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66970
telemt_connections_bad_total 5511
telemt_handshake_timeouts_total 1068
telemt_upstream_connect_attempt_total 30716
telemt_upstream_connect_success_total 30367
telemt_upstream_connect_fail_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 30716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 38287
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4762
telemt_me_idle_close_by_peer_total 4762
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12606
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33591
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4788
telemt_me_refill_failed_total 1084
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1104
telemt_user_connections_total{user="hello"} 58816
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 520943782 (496.81 MB)
telemt_user_octets_to_client{user="hello"} 18055964334 (16.82 GB)
telemt_user_msgs_from_client{user="hello"} 406265
telemt_user_msgs_to_client{user="hello"} 1683330
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28504.2 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177506
telemt_connections_bad_total 903
telemt_handshake_timeouts_total 1417
telemt_upstream_connect_attempt_total 5990
telemt_upstream_connect_success_total 5958
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 5569
telemt_me_reconnect_success_total 4506
telemt_me_reader_eof_total 4756
telemt_me_idle_close_by_peer_total 4755
telemt_me_route_drop_no_conn_total 69149
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169855
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4596
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4499
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 169814
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 3384275824 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 77194291312 (71.89 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 55
```