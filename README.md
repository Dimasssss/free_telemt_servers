# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 15:38:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 66735.6 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2334375
telemt_connections_bad_total 125483
telemt_connections_current 1663
telemt_connections_me_current 1663
telemt_handshake_timeouts_total 86085
telemt_upstream_connect_attempt_total 24723
telemt_upstream_connect_success_total 24722
telemt_upstream_connect_attempts_per_request{bucket="1"} 24722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1014
telemt_me_reconnect_success_total 423
telemt_me_reader_eof_total 425
telemt_me_idle_close_by_peer_total 425
telemt_me_route_drop_no_conn_total 1901422
telemt_me_route_drop_channel_closed_total 763
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1982777
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 521
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 9816
telemt_desync_full_logged_total 3029
telemt_desync_suppressed_total 6787
telemt_desync_frames_bucket_total{bucket="1_2"} 2646
telemt_desync_frames_bucket_total{bucket="3_10"} 3678
telemt_desync_frames_bucket_total{bucket="gt_10"} 3492
telemt_pool_swap_total 74
telemt_pool_force_close_total 2247
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 424
telemt_me_draining_writers_reap_progress_total 22556
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1640
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21127
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2200
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20309
telemt_me_writer_teardown_success_total{mode="normal"} 22767
telemt_me_writer_teardown_noop_total 22562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45329
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 201.765507
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45329
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 424
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 373
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1979496
telemt_user_connections_current{user="hello"} 1663
telemt_user_octets_from_client{user="hello"} 29997545000 (27.94 GB)
telemt_user_octets_to_client{user="hello"} 530618705984 (494.18 GB)
telemt_user_unique_ips_current{user="hello"} 639
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 80102.0 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3538838
telemt_connections_bad_total 321977
telemt_connections_current 1377
telemt_connections_me_current 1377
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 84957
telemt_upstream_connect_attempt_total 50615
telemt_upstream_connect_success_total 50001
telemt_upstream_connect_fail_total 542
telemt_upstream_connect_attempts_per_request{bucket="1"} 50543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 542
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5731
telemt_me_reconnect_success_total 1999
telemt_me_reader_eof_total 1930
telemt_me_idle_close_by_peer_total 1930
telemt_me_route_drop_no_conn_total 3513719
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2804257
telemt_me_endpoint_quarantine_total 643
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 618
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 88
telemt_desync_total 10842
telemt_desync_full_logged_total 6026
telemt_desync_suppressed_total 4816
telemt_desync_frames_bucket_total{bucket="1_2"} 2543
telemt_desync_frames_bucket_total{bucket="3_10"} 4279
telemt_desync_frames_bucket_total{bucket="gt_10"} 4020
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 31797
telemt_me_writer_removed_unexpected_total 1884
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3697
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29989
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29569
telemt_me_writer_teardown_success_total{mode="normal"} 33686
telemt_me_writer_teardown_noop_total 31797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65483
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.583288
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65483
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1709
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 2815615
telemt_user_connections_current{user="hello"} 1377
telemt_user_octets_from_client{user="hello"} 34419638163 (32.06 GB)
telemt_user_octets_to_client{user="hello"} 615842732758 (573.55 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 154961.8 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15161315
telemt_connections_bad_total 1390912
telemt_connections_current 2362
telemt_connections_me_current 2362
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 368541
telemt_upstream_connect_attempt_total 70295
telemt_upstream_connect_success_total 70200
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1667
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2588
telemt_me_reconnect_success_total 1336
telemt_me_reader_eof_total 1274
telemt_me_idle_close_by_peer_total 1272
telemt_me_route_drop_no_conn_total 13754016
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12132880
telemt_me_endpoint_quarantine_total 980
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1153
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 49106
telemt_desync_full_logged_total 15414
telemt_desync_suppressed_total 33692
telemt_desync_frames_bucket_total{bucket="1_2"} 11030
telemt_desync_frames_bucket_total{bucket="3_10"} 19203
telemt_desync_frames_bucket_total{bucket="gt_10"} 18873
telemt_pool_swap_total 167
telemt_pool_force_close_total 5664
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 925
telemt_me_draining_writers_reap_progress_total 50963
telemt_me_writer_removed_unexpected_total 1229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4440
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47058
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45299
telemt_me_writer_teardown_success_total{mode="normal"} 51498
telemt_me_writer_teardown_noop_total 51013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102511
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 291.573030
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102511
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 925
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 12134276
telemt_user_connections_current{user="hello"} 2362
telemt_user_octets_from_client{user="hello"} 170770434769 (159.04 GB)
telemt_user_octets_to_client{user="hello"} 3120331417423 (2.84 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 979
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 154963.2 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10939056
telemt_connections_bad_total 1056602
telemt_connections_current 1360
telemt_connections_me_current 1360
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 323845
telemt_upstream_connect_attempt_total 82468
telemt_upstream_connect_success_total 81316
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 82144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3893
telemt_me_reconnect_success_total 1575
telemt_me_reader_eof_total 1443
telemt_me_idle_close_by_peer_total 1443
telemt_me_route_drop_no_conn_total 4332375
telemt_me_route_drop_channel_closed_total 477
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8163932
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1172
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 36249
telemt_desync_full_logged_total 12171
telemt_desync_suppressed_total 24078
telemt_desync_frames_bucket_total{bucket="1_2"} 8890
telemt_desync_frames_bucket_total{bucket="3_10"} 13960
telemt_desync_frames_bucket_total{bucket="gt_10"} 13399
telemt_pool_swap_total 165
telemt_pool_force_close_total 5099
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 49250
telemt_me_writer_removed_unexpected_total 1475
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4544
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46038
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4625
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44151
telemt_me_writer_teardown_success_total{mode="normal"} 50582
telemt_me_writer_teardown_noop_total 49268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99850
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.066522
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99850
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1338
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8102756
telemt_user_connections_current{user="hello"} 1360
telemt_user_octets_from_client{user="hello"} 203284215749 (189.32 GB)
telemt_user_octets_to_client{user="hello"} 3652402744214 (3.32 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 154927.4 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10364494
telemt_connections_bad_total 889663
telemt_connections_current 1379
telemt_connections_me_current 1379
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 330280
telemt_upstream_connect_attempt_total 67692
telemt_upstream_connect_success_total 66765
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4621
telemt_me_reconnect_success_total 1863
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 5104575
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7825173
telemt_me_endpoint_quarantine_total 1065
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1136
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 35829
telemt_desync_full_logged_total 11876
telemt_desync_suppressed_total 23953
telemt_desync_frames_bucket_total{bucket="1_2"} 9062
telemt_desync_frames_bucket_total{bucket="3_10"} 13693
telemt_desync_frames_bucket_total{bucket="gt_10"} 13074
telemt_pool_swap_total 162
telemt_pool_force_close_total 5048
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 49703
telemt_me_writer_removed_unexpected_total 1760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4980
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46395
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44655
telemt_me_writer_teardown_success_total{mode="normal"} 51375
telemt_me_writer_teardown_noop_total 49774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101149
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3169.947133
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101149
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1614
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 7818256
telemt_user_connections_current{user="hello"} 1379
telemt_user_octets_from_client{user="hello"} 180539422869 (168.14 GB)
telemt_user_octets_to_client{user="hello"} 3248441969725 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 25207.3 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9985262
telemt_connections_bad_total 610951
telemt_connections_current 2115
telemt_connections_me_current 2115
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 170053
telemt_upstream_connect_attempt_total 34657
telemt_upstream_connect_success_total 32913
telemt_upstream_connect_fail_total 1245
telemt_upstream_connect_attempts_per_request{bucket="1"} 34158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1245
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5692
telemt_me_reconnect_success_total 671
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 415
telemt_me_route_drop_no_conn_total 24844354
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8322671
telemt_me_endpoint_quarantine_total 157
telemt_me_single_endpoint_outage_enter_total 47
telemt_me_single_endpoint_outage_exit_total 47
telemt_me_single_endpoint_outage_reconnect_attempt_total 81
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 81
telemt_me_single_endpoint_shadow_rotate_total 194
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 12648
telemt_desync_full_logged_total 3242
telemt_desync_suppressed_total 9406
telemt_desync_frames_bucket_total{bucket="1_2"} 2199
telemt_desync_frames_bucket_total{bucket="3_10"} 5133
telemt_desync_frames_bucket_total{bucket="gt_10"} 5316
telemt_pool_swap_total 23
telemt_pool_force_close_total 953
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 6748
telemt_me_writer_removed_unexpected_total 577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1162
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6127
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5795
telemt_me_writer_teardown_success_total{mode="normal"} 7289
telemt_me_writer_teardown_noop_total 6753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14042
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.166286
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14042
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 8340974
telemt_user_connections_current{user="hello"} 2115
telemt_user_octets_from_client{user="hello"} 55602800634 (51.78 GB)
telemt_user_octets_to_client{user="hello"} 262041177972 (244.04 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 791
telemt_user_unique_ips_recent_window{user="hello"} 314
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 154933.9 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10114916
telemt_connections_bad_total 842941
telemt_connections_current 1808
telemt_connections_me_current 1808
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 222525
telemt_upstream_connect_attempt_total 92520
telemt_upstream_connect_success_total 91558
telemt_upstream_connect_fail_total 817
telemt_upstream_connect_attempts_per_request{bucket="1"} 92375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1269
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 817
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71664
telemt_me_reconnect_success_total 2574
telemt_me_reader_eof_total 2285
telemt_me_idle_close_by_peer_total 2284
telemt_me_route_drop_no_conn_total 5030870
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7986128
telemt_me_endpoint_quarantine_total 1047
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 54
telemt_me_writers_warm_current 34
telemt_desync_total 41486
telemt_desync_full_logged_total 14166
telemt_desync_suppressed_total 27320
telemt_desync_frames_bucket_total{bucket="1_2"} 8437
telemt_desync_frames_bucket_total{bucket="3_10"} 16072
telemt_desync_frames_bucket_total{bucket="gt_10"} 16977
telemt_pool_swap_total 158
telemt_pool_force_close_total 4707
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 52742
telemt_me_writer_removed_unexpected_total 2330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5631
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49460
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 682
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48035
telemt_me_writer_teardown_success_total{mode="normal"} 55091
telemt_me_writer_teardown_noop_total 52743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.342912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 4262
telemt_me_writer_restored_same_endpoint_total 2170
telemt_me_writer_restored_fallback_total 43
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 7986335
telemt_user_connections_current{user="hello"} 1808
telemt_user_octets_from_client{user="hello"} 181019358611 (168.59 GB)
telemt_user_octets_to_client{user="hello"} 3002534874665 (2.73 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 749
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 91770.0 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10516318
telemt_connections_bad_total 387206
telemt_connections_current 1476
telemt_connections_me_current 1476
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4440415
telemt_upstream_connect_attempt_total 44347
telemt_upstream_connect_success_total 44022
telemt_upstream_connect_fail_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 44338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 316
telemt_me_reconnect_attempts_total 48034
telemt_me_reconnect_success_total 1498
telemt_me_reader_eof_total 1161
telemt_me_idle_close_by_peer_total 1160
telemt_me_route_drop_no_conn_total 3888415
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5035299
telemt_me_endpoint_quarantine_total 598
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 688
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27499
telemt_desync_full_logged_total 9279
telemt_desync_suppressed_total 18220
telemt_desync_frames_bucket_total{bucket="1_2"} 5550
telemt_desync_frames_bucket_total{bucket="3_10"} 10866
telemt_desync_frames_bucket_total{bucket="gt_10"} 11083
telemt_pool_swap_total 96
telemt_pool_force_close_total 2981
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 309
telemt_me_draining_writers_reap_progress_total 31474
telemt_me_writer_removed_unexpected_total 1224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2843
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29885
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2562
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28493
telemt_me_writer_teardown_success_total{mode="normal"} 32728
telemt_me_writer_teardown_noop_total 31481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64209
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.609117
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64209
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 309
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1332
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5028978
telemt_user_connections_current{user="hello"} 1476
telemt_user_octets_from_client{user="hello"} 108559904144 (101.10 GB)
telemt_user_octets_to_client{user="hello"} 1894379346438 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 72740.7 (20h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942539
telemt_connections_bad_total 12770
telemt_connections_current 1049
telemt_connections_me_current 1049
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18359
telemt_upstream_connect_attempt_total 35992
telemt_upstream_connect_success_total 35902
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 35976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 1617
telemt_me_reconnect_success_total 685
telemt_me_reader_eof_total 660
telemt_me_idle_close_by_peer_total 660
telemt_me_route_drop_no_conn_total 324048
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837903
telemt_me_endpoint_quarantine_total 634
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 604
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 4659
telemt_desync_full_logged_total 1418
telemt_desync_suppressed_total 3241
telemt_desync_frames_bucket_total{bucket="1_2"} 1093
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 1721
telemt_pool_swap_total 77
telemt_pool_force_close_total 1938
telemt_me_writer_close_signal_drop_total 111
telemt_me_draining_writers_reap_progress_total 29744
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28111
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1860
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27806
telemt_me_writer_teardown_success_total{mode="normal"} 30406
telemt_me_writer_teardown_noop_total 29746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60152
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.474137
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60152
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 111
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 838956
telemt_user_connections_current{user="hello"} 1049
telemt_user_octets_from_client{user="hello"} 15277732061 (14.23 GB)
telemt_user_octets_to_client{user="hello"} 379747149503 (353.67 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 154938.4 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12400090
telemt_connections_bad_total 1441148
telemt_connections_current 1817
telemt_connections_me_current 1817
telemt_handshake_timeouts_total 339945
telemt_upstream_connect_attempt_total 58041
telemt_upstream_connect_success_total 57814
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 57991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2261
telemt_me_reconnect_success_total 1204
telemt_me_reader_eof_total 1169
telemt_me_idle_close_by_peer_total 1169
telemt_me_route_drop_no_conn_total 4140021
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9368811
telemt_me_endpoint_quarantine_total 1051
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1156
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 38405
telemt_desync_full_logged_total 12544
telemt_desync_suppressed_total 25861
telemt_desync_frames_bucket_total{bucket="1_2"} 9126
telemt_desync_frames_bucket_total{bucket="3_10"} 14233
telemt_desync_frames_bucket_total{bucket="gt_10"} 15046
telemt_pool_swap_total 172
telemt_pool_force_close_total 4736
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 610
telemt_me_draining_writers_reap_progress_total 52269
telemt_me_writer_removed_unexpected_total 1123
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4291
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49133
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4563
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47533
telemt_me_writer_teardown_success_total{mode="normal"} 53424
telemt_me_writer_teardown_noop_total 52271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.880754
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 610
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1054
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9338184
telemt_user_connections_current{user="hello"} 1817
telemt_user_octets_from_client{user="hello"} 181905170476 (169.41 GB)
telemt_user_octets_to_client{user="hello"} 4127101399332 (3.75 TB)
telemt_user_unique_ips_current{user="hello"} 685
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 154935.0 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10742745
telemt_connections_bad_total 1199601
telemt_connections_current 1615
telemt_connections_me_current 1615
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 277392
telemt_upstream_connect_attempt_total 83856
telemt_upstream_connect_success_total 83229
telemt_upstream_connect_fail_total 543
telemt_upstream_connect_attempts_per_request{bucket="1"} 83772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 543
telemt_me_reconnect_attempts_total 8869
telemt_me_reconnect_success_total 2032
telemt_me_reader_eof_total 1899
telemt_me_idle_close_by_peer_total 1899
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5387972
telemt_me_route_drop_channel_closed_total 344
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8302691
telemt_me_endpoint_quarantine_total 1179
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1158
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 37992
telemt_desync_full_logged_total 12276
telemt_desync_suppressed_total 25716
telemt_desync_frames_bucket_total{bucket="1_2"} 9452
telemt_desync_frames_bucket_total{bucket="3_10"} 14161
telemt_desync_frames_bucket_total{bucket="gt_10"} 14379
telemt_pool_swap_total 164
telemt_pool_force_close_total 4582
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 597
telemt_me_draining_writers_reap_progress_total 51739
telemt_me_writer_removed_unexpected_total 1926
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5388
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48344
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4143
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47157
telemt_me_writer_teardown_success_total{mode="normal"} 53732
telemt_me_writer_teardown_noop_total 51744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105476
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.325285
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105476
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 597
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1654
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8308756
telemt_user_connections_current{user="hello"} 1615
telemt_user_octets_from_client{user="hello"} 146428824229 (136.37 GB)
telemt_user_octets_to_client{user="hello"} 3170823111755 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 212
```