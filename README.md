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

# Server Metrics 2026-03-22 01:44:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 16704.7 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241427
telemt_connections_bad_total 17172
telemt_connections_current 651
telemt_connections_me_current 651
telemt_handshake_timeouts_total 13961
telemt_upstream_connect_attempt_total 6954
telemt_upstream_connect_success_total 6953
telemt_upstream_connect_attempts_per_request{bucket="1"} 6953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 234
telemt_me_reconnect_success_total 110
telemt_me_reader_eof_total 108
telemt_me_idle_close_by_peer_total 108
telemt_me_route_drop_no_conn_total 45000
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196974
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 45
telemt_desync_total 1722
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1245
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 18
telemt_pool_force_close_total 468
telemt_me_writer_close_signal_drop_total 33
telemt_me_draining_writers_reap_progress_total 6245
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 437
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5906
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5777
telemt_me_writer_teardown_success_total{mode="normal"} 6343
telemt_me_writer_teardown_noop_total 6246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12589
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.148766
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12589
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 33
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 100
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 196663
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 2136200980 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 68445057764 (63.74 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 30070.7 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746753
telemt_connections_bad_total 43113
telemt_connections_current 434
telemt_connections_me_current 434
telemt_handshake_timeouts_total 27786
telemt_upstream_connect_attempt_total 13760
telemt_upstream_connect_success_total 13539
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 13740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_reconnect_attempts_total 1158
telemt_me_reconnect_success_total 428
telemt_me_reader_eof_total 378
telemt_me_idle_close_by_peer_total 378
telemt_me_route_drop_no_conn_total 335866
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 596848
telemt_me_endpoint_quarantine_total 283
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_writers_active_current 46
telemt_desync_total 2619
telemt_desync_full_logged_total 1495
telemt_desync_suppressed_total 1124
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 1072
telemt_pool_swap_total 32
telemt_pool_force_close_total 884
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 12189
telemt_me_writer_removed_unexpected_total 360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11515
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11305
telemt_me_writer_teardown_success_total{mode="normal"} 12554
telemt_me_writer_teardown_noop_total 12189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24743
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.504428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24743
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 314
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 595967
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 9911860096 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 214008319720 (199.31 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 104930.5 (29h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7633582
telemt_connections_bad_total 619205
telemt_connections_current 1525
telemt_connections_me_current 1525
telemt_handshake_timeouts_total 250024
telemt_upstream_connect_attempt_total 38655
telemt_upstream_connect_success_total 38582
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 38589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1552
telemt_me_reconnect_success_total 788
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 799
telemt_me_route_drop_no_conn_total 4522692
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6195790
telemt_me_endpoint_quarantine_total 675
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 783
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26217
telemt_desync_full_logged_total 8663
telemt_desync_suppressed_total 17554
telemt_desync_frames_bucket_total{bucket="1_2"} 5641
telemt_desync_frames_bucket_total{bucket="3_10"} 10226
telemt_desync_frames_bucket_total{bucket="gt_10"} 10350
telemt_pool_swap_total 113
telemt_pool_force_close_total 3784
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 35263
telemt_me_writer_removed_unexpected_total 768
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2952
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32623
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31479
telemt_me_writer_teardown_success_total{mode="normal"} 35575
telemt_me_writer_teardown_noop_total 35307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70882
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.420809
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70882
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 704
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6188029
telemt_user_connections_current{user="hello"} 1525
telemt_user_octets_from_client{user="hello"} 105618337872 (98.36 GB)
telemt_user_octets_to_client{user="hello"} 2051803659964 (1.87 TB)
telemt_user_unique_ips_current{user="hello"} 782
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 104931.9 (29h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6291054
telemt_connections_bad_total 584133
telemt_connections_current 1459
telemt_connections_me_current 1459
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 208724
telemt_upstream_connect_attempt_total 42671
telemt_upstream_connect_success_total 42286
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 42474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1907
telemt_me_reconnect_success_total 854
telemt_me_reader_eof_total 824
telemt_me_idle_close_by_peer_total 824
telemt_me_route_drop_no_conn_total 2245035
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4716760
telemt_me_endpoint_quarantine_total 651
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 807
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22401
telemt_desync_full_logged_total 7612
telemt_desync_suppressed_total 14789
telemt_desync_frames_bucket_total{bucket="1_2"} 5395
telemt_desync_frames_bucket_total{bucket="3_10"} 8689
telemt_desync_frames_bucket_total{bucket="gt_10"} 8317
telemt_pool_swap_total 114
telemt_pool_force_close_total 3419
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 33788
telemt_me_writer_removed_unexpected_total 809
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31673
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30369
telemt_me_writer_teardown_success_total{mode="normal"} 34534
telemt_me_writer_teardown_noop_total 33794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.227975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4639019
telemt_user_connections_current{user="hello"} 1459
telemt_user_octets_from_client{user="hello"} 139552858197 (129.97 GB)
telemt_user_octets_to_client{user="hello"} 2182739141807 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 737
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 104896.1 (29h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6184379
telemt_connections_bad_total 545254
telemt_connections_current 1418
telemt_connections_me_current 1418
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 198514
telemt_upstream_connect_attempt_total 48957
telemt_upstream_connect_success_total 48608
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 48744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1060
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1951
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 821
telemt_me_idle_close_by_peer_total 821
telemt_me_route_drop_no_conn_total 2137916
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4610864
telemt_me_endpoint_quarantine_total 730
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 787
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 22210
telemt_desync_full_logged_total 7447
telemt_desync_suppressed_total 14763
telemt_desync_frames_bucket_total{bucket="1_2"} 5427
telemt_desync_frames_bucket_total{bucket="3_10"} 8508
telemt_desync_frames_bucket_total{bucket="gt_10"} 8275
telemt_pool_swap_total 113
telemt_pool_force_close_total 3291
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 35135
telemt_me_writer_removed_unexpected_total 794
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33029
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3076
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31844
telemt_me_writer_teardown_success_total{mode="normal"} 35942
telemt_me_writer_teardown_noop_total 35146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71088
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.749769
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71088
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4606579
telemt_user_connections_current{user="hello"} 1418
telemt_user_octets_from_client{user="hello"} 132977010215 (123.84 GB)
telemt_user_octets_to_client{user="hello"} 2104030540179 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 104935.5 (29h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20259473
telemt_connections_bad_total 1569795
telemt_connections_current 1982
telemt_connections_me_current 1982
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 595353
telemt_upstream_connect_attempt_total 194009
telemt_upstream_connect_success_total 176089
telemt_upstream_connect_fail_total 16220
telemt_upstream_connect_attempts_per_request{bucket="1"} 192309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8911
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16220
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64770
telemt_me_reconnect_success_total 2274
telemt_me_reader_eof_total 1411
telemt_me_idle_close_by_peer_total 1410
telemt_me_route_drop_no_conn_total 39488397
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16417096
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 816
telemt_me_single_endpoint_outage_enter_total 133
telemt_me_single_endpoint_outage_exit_total 133
telemt_me_single_endpoint_outage_reconnect_attempt_total 283
telemt_me_single_endpoint_outage_reconnect_success_total 68
telemt_me_single_endpoint_quarantine_bypass_total 283
telemt_me_single_endpoint_shadow_rotate_total 823
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 31815
telemt_desync_full_logged_total 9510
telemt_desync_suppressed_total 22305
telemt_desync_frames_bucket_total{bucket="1_2"} 6895
telemt_desync_frames_bucket_total{bucket="3_10"} 14118
telemt_desync_frames_bucket_total{bucket="gt_10"} 10802
telemt_pool_swap_total 108
telemt_pool_force_close_total 3548
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 788
telemt_me_draining_writers_reap_progress_total 32719
telemt_me_writer_removed_unexpected_total 2114
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30126
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29171
telemt_me_writer_teardown_success_total{mode="normal"} 34569
telemt_me_writer_teardown_noop_total 32745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67314
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 213.704726
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67314
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 788
telemt_me_refill_failed_total 3799
telemt_me_writer_restored_same_endpoint_total 1557
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 16546683
telemt_user_connections_current{user="hello"} 1982
telemt_user_octets_from_client{user="hello"} 206701288390 (192.51 GB)
telemt_user_octets_to_client{user="hello"} 1171203884963 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 104902.9 (29h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5947795
telemt_connections_bad_total 557942
telemt_connections_current 1474
telemt_connections_me_current 1474
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 124235
telemt_upstream_connect_attempt_total 57335
telemt_upstream_connect_success_total 56665
telemt_upstream_connect_fail_total 573
telemt_upstream_connect_attempts_per_request{bucket="1"} 57238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 573
telemt_me_reconnect_attempts_total 69588
telemt_me_reconnect_success_total 1760
telemt_me_reader_eof_total 1535
telemt_me_idle_close_by_peer_total 1534
telemt_me_route_drop_no_conn_total 2377781
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4641320
telemt_me_endpoint_quarantine_total 710
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 792
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 23229
telemt_desync_full_logged_total 8162
telemt_desync_suppressed_total 15067
telemt_desync_frames_bucket_total{bucket="1_2"} 4413
telemt_desync_frames_bucket_total{bucket="3_10"} 8991
telemt_desync_frames_bucket_total{bucket="gt_10"} 9825
telemt_pool_swap_total 108
telemt_pool_force_close_total 3135
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 36701
telemt_me_writer_removed_unexpected_total 1576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3814
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34491
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2734
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33566
telemt_me_writer_teardown_success_total{mode="normal"} 38305
telemt_me_writer_teardown_noop_total 36702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.095574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 4204
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 4634267
telemt_user_connections_current{user="hello"} 1474
telemt_user_octets_from_client{user="hello"} 123320076596 (114.85 GB)
telemt_user_octets_to_client{user="hello"} 1894132815586 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 41738.6 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3839542
telemt_connections_bad_total 139297
telemt_connections_current 1099
telemt_connections_me_current 1099
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1575226
telemt_upstream_connect_attempt_total 25742
telemt_upstream_connect_success_total 25573
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 25735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_reconnect_attempts_total 45779
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 621
telemt_me_idle_close_by_peer_total 621
telemt_me_route_drop_no_conn_total 1012609
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1875464
telemt_me_endpoint_quarantine_total 312
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 320
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 10287
telemt_desync_full_logged_total 3545
telemt_desync_suppressed_total 6742
telemt_desync_frames_bucket_total{bucket="1_2"} 1830
telemt_desync_frames_bucket_total{bucket="3_10"} 3949
telemt_desync_frames_bucket_total{bucket="gt_10"} 4508
telemt_pool_swap_total 45
telemt_pool_force_close_total 1408
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 131
telemt_me_draining_writers_reap_progress_total 14921
telemt_me_writer_removed_unexpected_total 698
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1451
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14191
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1202
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13513
telemt_me_writer_teardown_success_total{mode="normal"} 15642
telemt_me_writer_teardown_noop_total 14923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30565
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.337665
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30565
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 131
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 844
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1879145
telemt_user_connections_current{user="hello"} 1099
telemt_user_octets_from_client{user="hello"} 53512851732 (49.84 GB)
telemt_user_octets_to_client{user="hello"} 801038603830 (746.03 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 22709.3 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183449
telemt_connections_bad_total 1618
telemt_connections_current 263
telemt_connections_me_current 263
telemt_handshake_timeouts_total 5055
telemt_upstream_connect_attempt_total 10872
telemt_upstream_connect_success_total 10847
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 228
telemt_me_reconnect_success_total 142
telemt_me_reader_eof_total 145
telemt_me_idle_close_by_peer_total 145
telemt_me_route_drop_no_conn_total 50330
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161429
telemt_me_endpoint_quarantine_total 230
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 43
telemt_desync_total 1008
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 25
telemt_pool_force_close_total 559
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 9795
telemt_me_writer_removed_unexpected_total 140
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9291
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9236
telemt_me_writer_teardown_success_total{mode="normal"} 9940
telemt_me_writer_teardown_noop_total 9795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19735
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.944820
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19735
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 131
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 161128
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 2956531404 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 92877366868 (86.50 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 104907.1 (29h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7219258
telemt_connections_bad_total 735809
telemt_connections_current 1616
telemt_connections_me_current 1616
telemt_handshake_timeouts_total 205867
telemt_upstream_connect_attempt_total 40819
telemt_upstream_connect_success_total 40665
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 40782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1545
telemt_me_reconnect_success_total 828
telemt_me_reader_eof_total 810
telemt_me_idle_close_by_peer_total 810
telemt_me_route_drop_no_conn_total 2115366
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5420598
telemt_me_endpoint_quarantine_total 727
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 807
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
telemt_me_writers_active_current 47
telemt_desync_total 21326
telemt_desync_full_logged_total 6993
telemt_desync_suppressed_total 14333
telemt_desync_frames_bucket_total{bucket="1_2"} 5357
telemt_desync_frames_bucket_total{bucket="3_10"} 7720
telemt_desync_frames_bucket_total{bucket="gt_10"} 8249
telemt_pool_swap_total 116
telemt_pool_force_close_total 3128
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 36777
telemt_me_writer_removed_unexpected_total 781
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34658
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33649
telemt_me_writer_teardown_success_total{mode="normal"} 37577
telemt_me_writer_teardown_noop_total 36779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.613517
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 738
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5395647
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 108629602720 (101.17 GB)
telemt_user_octets_to_client{user="hello"} 2519739815024 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 104903.9 (29h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6223065
telemt_connections_bad_total 613499
telemt_connections_current 1482
telemt_connections_me_current 1482
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 170773
telemt_upstream_connect_attempt_total 56613
telemt_upstream_connect_success_total 56191
telemt_upstream_connect_fail_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 56554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 363
telemt_me_reconnect_attempts_total 5506
telemt_me_reconnect_success_total 1141
telemt_me_reader_eof_total 1023
telemt_me_idle_close_by_peer_total 1023
telemt_me_seq_mismatch_total 45
telemt_me_route_drop_no_conn_total 2168843
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4788566
telemt_me_endpoint_quarantine_total 834
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 803
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 19953
telemt_desync_full_logged_total 6626
telemt_desync_suppressed_total 13327
telemt_desync_frames_bucket_total{bucket="1_2"} 5090
telemt_desync_frames_bucket_total{bucket="3_10"} 7265
telemt_desync_frames_bucket_total{bucket="gt_10"} 7598
telemt_pool_swap_total 114
telemt_pool_force_close_total 3085
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 35353
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3432
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33004
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32268
telemt_me_writer_teardown_success_total{mode="normal"} 36436
telemt_me_writer_teardown_noop_total 35357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71793
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.991689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71793
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 889
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4791683
telemt_user_connections_current{user="hello"} 1482
telemt_user_octets_from_client{user="hello"} 89999208677 (83.82 GB)
telemt_user_octets_to_client{user="hello"} 2049851323692 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 718
telemt_user_unique_ips_recent_window{user="hello"} 131
```