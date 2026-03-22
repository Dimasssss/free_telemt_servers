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

# Server Metrics 2026-03-22 12:43:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 56247.4 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1697580
telemt_connections_bad_total 78768
telemt_connections_current 1714
telemt_connections_me_current 1714
telemt_handshake_timeouts_total 74842
telemt_upstream_connect_attempt_total 21300
telemt_upstream_connect_success_total 21299
telemt_upstream_connect_attempts_per_request{bucket="1"} 21299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 889
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 350
telemt_me_idle_close_by_peer_total 350
telemt_me_route_drop_no_conn_total 1131609
telemt_me_route_drop_channel_closed_total 512
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1436874
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 398
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 447
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 8428
telemt_desync_full_logged_total 2555
telemt_desync_suppressed_total 5873
telemt_desync_frames_bucket_total{bucket="1_2"} 2366
telemt_desync_frames_bucket_total{bucket="3_10"} 3179
telemt_desync_frames_bucket_total{bucket="gt_10"} 2883
telemt_pool_swap_total 62
telemt_pool_force_close_total 1853
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 284
telemt_me_draining_writers_reap_progress_total 19426
telemt_me_writer_removed_unexpected_total 342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1379
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18264
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1818
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17573
telemt_me_writer_teardown_success_total{mode="normal"} 19643
telemt_me_writer_teardown_noop_total 19428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 137.710973
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 284
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 306
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1434097
telemt_user_connections_current{user="hello"} 1714
telemt_user_octets_from_client{user="hello"} 22904008488 (21.33 GB)
telemt_user_octets_to_client{user="hello"} 424774317196 (395.60 GB)
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 69613.2 (19h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2736262
telemt_connections_bad_total 255797
telemt_connections_current 1277
telemt_connections_me_current 1277
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 64260
telemt_upstream_connect_attempt_total 45706
telemt_upstream_connect_success_total 45172
telemt_upstream_connect_fail_total 473
telemt_upstream_connect_attempts_per_request{bucket="1"} 45645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 473
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3481
telemt_me_reconnect_success_total 1579
telemt_me_reader_eof_total 1461
telemt_me_idle_close_by_peer_total 1461
telemt_me_route_drop_no_conn_total 2407469
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2142588
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 545
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 8529
telemt_desync_full_logged_total 4796
telemt_desync_suppressed_total 3733
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 3315
telemt_desync_frames_bucket_total{bucket="gt_10"} 3207
telemt_pool_swap_total 69
telemt_pool_force_close_total 1975
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 27771
telemt_me_writer_removed_unexpected_total 1421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26148
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1737
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25796
telemt_me_writer_teardown_success_total{mode="normal"} 29192
telemt_me_writer_teardown_noop_total 27771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56963
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.012972
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56963
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1316
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2154293
telemt_user_connections_current{user="hello"} 1277
telemt_user_octets_from_client{user="hello"} 26621492635 (24.79 GB)
telemt_user_octets_to_client{user="hello"} 522366486710 (486.49 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 796
telemt_user_unique_ips_recent_window{user="hello"} 595
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 144473.0 (40h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13040671
telemt_connections_bad_total 1152997
telemt_connections_current 5072
telemt_connections_me_current 5072
telemt_handshake_timeouts_total 337729
telemt_upstream_connect_attempt_total 52590
telemt_upstream_connect_success_total 52510
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2378
telemt_me_reconnect_success_total 1228
telemt_me_reader_eof_total 1191
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 10736949
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10420178
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1074
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 42917
telemt_desync_full_logged_total 13694
telemt_desync_suppressed_total 29223
telemt_desync_frames_bucket_total{bucket="1_2"} 9703
telemt_desync_frames_bucket_total{bucket="3_10"} 16756
telemt_desync_frames_bucket_total{bucket="gt_10"} 16458
telemt_pool_swap_total 155
telemt_pool_force_close_total 5294
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 837
telemt_me_draining_writers_reap_progress_total 47963
telemt_me_writer_removed_unexpected_total 1149
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4169
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44300
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4875
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42669
telemt_me_writer_teardown_success_total{mode="normal"} 48469
telemt_me_writer_teardown_noop_total 48011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96480
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 233.580718
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96480
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 837
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1064
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 10408560
telemt_user_connections_current{user="hello"} 5072
telemt_user_octets_from_client{user="hello"} 153639431712 (143.09 GB)
telemt_user_octets_to_client{user="hello"} 2881988413696 (2.62 TB)
telemt_user_unique_ips_current{user="hello"} 2046
telemt_user_unique_ips_recent_window{user="hello"} 799
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 144474.7 (40h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9835602
telemt_connections_bad_total 903417
telemt_connections_current 5364
telemt_connections_me_current 5364
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 296706
telemt_upstream_connect_attempt_total 78978
telemt_upstream_connect_success_total 77847
telemt_upstream_connect_fail_total 815
telemt_upstream_connect_attempts_per_request{bucket="1"} 78662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3672
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 815
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3382
telemt_me_reconnect_success_total 1406
telemt_me_reader_eof_total 1292
telemt_me_idle_close_by_peer_total 1292
telemt_me_route_drop_no_conn_total 3943650
telemt_me_route_drop_channel_closed_total 407
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7336021
telemt_me_endpoint_quarantine_total 904
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1100
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 33153
telemt_desync_full_logged_total 11197
telemt_desync_suppressed_total 21956
telemt_desync_frames_bucket_total{bucket="1_2"} 8144
telemt_desync_frames_bucket_total{bucket="3_10"} 12768
telemt_desync_frames_bucket_total{bucket="gt_10"} 12241
telemt_pool_swap_total 154
telemt_pool_force_close_total 4706
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 575
telemt_me_draining_writers_reap_progress_total 46190
telemt_me_writer_removed_unexpected_total 1323
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4155
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43226
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41484
telemt_me_writer_teardown_success_total{mode="normal"} 47381
telemt_me_writer_teardown_noop_total 46201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93582
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 83.183752
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93582
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 575
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 7276357
telemt_user_connections_current{user="hello"} 5364
telemt_user_octets_from_client{user="hello"} 188042479441 (175.13 GB)
telemt_user_octets_to_client{user="hello"} 3304316081978 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2140
telemt_user_unique_ips_recent_window{user="hello"} 620
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 144438.7 (40h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9270377
telemt_connections_bad_total 783699
telemt_connections_current 3392
telemt_connections_me_current 3392
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 294752
telemt_upstream_connect_attempt_total 64242
telemt_upstream_connect_success_total 63487
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1964
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3886
telemt_me_reconnect_success_total 1686
telemt_me_reader_eof_total 1508
telemt_me_idle_close_by_peer_total 1507
telemt_me_route_drop_no_conn_total 4015292
telemt_me_route_drop_channel_closed_total 290
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6982349
telemt_me_endpoint_quarantine_total 992
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1059
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 42
telemt_desync_total 32985
telemt_desync_full_logged_total 10943
telemt_desync_suppressed_total 22042
telemt_desync_frames_bucket_total{bucket="1_2"} 8382
telemt_desync_frames_bucket_total{bucket="3_10"} 12617
telemt_desync_frames_bucket_total{bucket="gt_10"} 11986
telemt_pool_swap_total 151
telemt_pool_force_close_total 4700
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 610
telemt_me_draining_writers_reap_progress_total 46968
telemt_me_writer_removed_unexpected_total 1588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4561
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43917
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 490
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42268
telemt_me_writer_teardown_success_total{mode="normal"} 48478
telemt_me_writer_teardown_noop_total 47035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3093.063747
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 610
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1467
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 6973999
telemt_user_connections_current{user="hello"} 3392
telemt_user_octets_from_client{user="hello"} 168159990061 (156.61 GB)
telemt_user_octets_to_client{user="hello"} 2979122361401 (2.71 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1394
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 14718.6 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6234282
telemt_connections_bad_total 389457
telemt_connections_current 6285
telemt_connections_me_current 6285
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 97926
telemt_upstream_connect_attempt_total 24401
telemt_upstream_connect_success_total 23306
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 24144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4633
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 524
telemt_me_reconnect_attempts_total 2345
telemt_me_reconnect_success_total 371
telemt_me_reader_eof_total 238
telemt_me_idle_close_by_peer_total 238
telemt_me_route_drop_no_conn_total 14817529
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5204409
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 121
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 7940
telemt_desync_full_logged_total 2007
telemt_desync_suppressed_total 5933
telemt_desync_frames_bucket_total{bucket="1_2"} 1428
telemt_desync_frames_bucket_total{bucket="3_10"} 3168
telemt_desync_frames_bucket_total{bucket="gt_10"} 3344
telemt_pool_swap_total 14
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 3843
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 647
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3479
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 424
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3273
telemt_me_writer_teardown_success_total{mode="normal"} 4126
telemt_me_writer_teardown_noop_total 3846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7972
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.599912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7972
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 5217730
telemt_user_connections_current{user="hello"} 6286
telemt_user_octets_from_client{user="hello"} 28372446394 (26.42 GB)
telemt_user_octets_to_client{user="hello"} 152578574751 (142.10 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2346
telemt_user_unique_ips_recent_window{user="hello"} 1315
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 144445.4 (40h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9044884
telemt_connections_bad_total 760078
telemt_connections_current 5157
telemt_connections_me_current 5157
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 193364
telemt_upstream_connect_attempt_total 88773
telemt_upstream_connect_success_total 87899
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 88651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71136
telemt_me_reconnect_success_total 2370
telemt_me_reader_eof_total 2111
telemt_me_idle_close_by_peer_total 2110
telemt_me_route_drop_no_conn_total 4342918
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7146397
telemt_me_endpoint_quarantine_total 966
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1080
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 42
telemt_desync_total 36570
telemt_desync_full_logged_total 12547
telemt_desync_suppressed_total 24023
telemt_desync_frames_bucket_total{bucket="1_2"} 7454
telemt_desync_frames_bucket_total{bucket="3_10"} 14072
telemt_desync_frames_bucket_total{bucket="gt_10"} 15044
telemt_pool_swap_total 148
telemt_pool_force_close_total 4355
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 525
telemt_me_draining_writers_reap_progress_total 49556
telemt_me_writer_removed_unexpected_total 2139
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5227
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46494
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3761
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 594
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45201
telemt_me_writer_teardown_success_total{mode="normal"} 51721
telemt_me_writer_teardown_noop_total 49557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.057070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 525
telemt_me_refill_failed_total 4245
telemt_me_writer_restored_same_endpoint_total 1989
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 7148543
telemt_user_connections_current{user="hello"} 5157
telemt_user_octets_from_client{user="hello"} 167612169819 (156.10 GB)
telemt_user_octets_to_client{user="hello"} 2749285472421 (2.50 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2040
telemt_user_unique_ips_recent_window{user="hello"} 653
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 81281.5 (22h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8651671
telemt_connections_bad_total 305274
telemt_connections_current 3915
telemt_connections_me_current 3915
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3632989
telemt_upstream_connect_attempt_total 41037
telemt_upstream_connect_success_total 40746
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 41029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47861
telemt_me_reconnect_success_total 1415
telemt_me_reader_eof_total 1084
telemt_me_idle_close_by_peer_total 1084
telemt_me_route_drop_no_conn_total 3012167
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4198853
telemt_me_endpoint_quarantine_total 542
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 614
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 23141
telemt_desync_full_logged_total 7736
telemt_desync_suppressed_total 15405
telemt_desync_frames_bucket_total{bucket="1_2"} 4738
telemt_desync_frames_bucket_total{bucket="3_10"} 9040
telemt_desync_frames_bucket_total{bucket="gt_10"} 9363
telemt_pool_swap_total 85
telemt_pool_force_close_total 2637
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 270
telemt_me_draining_writers_reap_progress_total 28531
telemt_me_writer_removed_unexpected_total 1149
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2584
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27124
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25894
telemt_me_writer_teardown_success_total{mode="normal"} 29708
telemt_me_writer_teardown_noop_total 28538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58246
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.841370
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58246
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 270
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1266
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4194589
telemt_user_connections_current{user="hello"} 3915
telemt_user_octets_from_client{user="hello"} 93861069436 (87.41 GB)
telemt_user_octets_to_client{user="hello"} 1641768763270 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1510
telemt_user_unique_ips_recent_window{user="hello"} 580
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 62252.2 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703318
telemt_connections_bad_total 8216
telemt_connections_current 988
telemt_connections_me_current 988
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13649
telemt_upstream_connect_attempt_total 31914
telemt_upstream_connect_success_total 31835
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 31902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 1402
telemt_me_reconnect_success_total 610
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 591
telemt_me_route_drop_no_conn_total 235393
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634937
telemt_me_endpoint_quarantine_total 568
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 520
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 3435
telemt_desync_full_logged_total 1014
telemt_desync_suppressed_total 2421
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 1363
telemt_desync_frames_bucket_total{bucket="gt_10"} 1222
telemt_pool_swap_total 66
telemt_pool_force_close_total 1598
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 26111
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24713
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24513
telemt_me_writer_teardown_success_total{mode="normal"} 26703
telemt_me_writer_teardown_noop_total 26113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52816
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.857981
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52816
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 529
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 636684
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 12225417637 (11.39 GB)
telemt_user_octets_to_client{user="hello"} 307342746499 (286.24 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 144449.7 (40h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11029820
telemt_connections_bad_total 1275731
telemt_connections_current 6274
telemt_connections_me_current 6274
telemt_handshake_timeouts_total 296030
telemt_upstream_connect_attempt_total 54835
telemt_upstream_connect_success_total 54622
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 54787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2151
telemt_me_reconnect_success_total 1144
telemt_me_reader_eof_total 1107
telemt_me_idle_close_by_peer_total 1107
telemt_me_route_drop_no_conn_total 3458391
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8285389
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1085
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 33680
telemt_desync_full_logged_total 11041
telemt_desync_suppressed_total 22639
telemt_desync_frames_bucket_total{bucket="1_2"} 8078
telemt_desync_frames_bucket_total{bucket="3_10"} 12465
telemt_desync_frames_bucket_total{bucket="gt_10"} 13137
telemt_pool_swap_total 160
telemt_pool_force_close_total 4380
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 547
telemt_me_draining_writers_reap_progress_total 49420
telemt_me_writer_removed_unexpected_total 1063
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4032
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46486
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45040
telemt_me_writer_teardown_success_total{mode="normal"} 50518
telemt_me_writer_teardown_noop_total 49422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.598869
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 547
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 1000
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 8256413
telemt_user_connections_current{user="hello"} 6274
telemt_user_octets_from_client{user="hello"} 158088263268 (147.23 GB)
telemt_user_octets_to_client{user="hello"} 3737104237340 (3.40 TB)
telemt_user_unique_ips_current{user="hello"} 2258
telemt_user_unique_ips_recent_window{user="hello"} 689
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 144446.5 (40h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9571671
telemt_connections_bad_total 1074866
telemt_connections_current 3595
telemt_connections_me_current 3595
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 248694
telemt_upstream_connect_attempt_total 80106
telemt_upstream_connect_success_total 79522
telemt_upstream_connect_fail_total 506
telemt_upstream_connect_attempts_per_request{bucket="1"} 80028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1996
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 506
telemt_me_reconnect_attempts_total 8491
telemt_me_reconnect_success_total 1862
telemt_me_reader_eof_total 1733
telemt_me_idle_close_by_peer_total 1733
telemt_me_seq_mismatch_total 70
telemt_me_route_drop_no_conn_total 4142942
telemt_me_route_drop_channel_closed_total 302
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7359864
telemt_me_endpoint_quarantine_total 1107
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1091
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_me_writers_active_current 42
telemt_desync_total 33112
telemt_desync_full_logged_total 10822
telemt_desync_suppressed_total 22290
telemt_desync_frames_bucket_total{bucket="1_2"} 8207
telemt_desync_frames_bucket_total{bucket="3_10"} 12324
telemt_desync_frames_bucket_total{bucket="gt_10"} 12581
telemt_pool_swap_total 154
telemt_pool_force_close_total 4256
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 537
telemt_me_draining_writers_reap_progress_total 48514
telemt_me_writer_removed_unexpected_total 1758
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4996
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45341
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44258
telemt_me_writer_teardown_success_total{mode="normal"} 50337
telemt_me_writer_teardown_noop_total 48518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.323242
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 537
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1506
telemt_me_writer_restored_fallback_total 94
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 7367428
telemt_user_connections_current{user="hello"} 3595
telemt_user_octets_from_client{user="hello"} 129802954481 (120.89 GB)
telemt_user_octets_to_client{user="hello"} 2937824251275 (2.67 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1573
telemt_user_unique_ips_recent_window{user="hello"} 575
```