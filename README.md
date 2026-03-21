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

# Server Metrics 2026-03-21 23:01:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 6937.3 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119581
telemt_connections_bad_total 9347
telemt_connections_current 636
telemt_connections_me_current 636
telemt_handshake_timeouts_total 5634
telemt_upstream_connect_attempt_total 2688
telemt_upstream_connect_success_total 2687
telemt_upstream_connect_attempts_per_request{bucket="1"} 2687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 68
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 35
telemt_me_idle_close_by_peer_total 35
telemt_me_route_drop_no_conn_total 24518
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96966
telemt_me_endpoint_quarantine_total 43
telemt_me_single_endpoint_shadow_rotate_total 61
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
telemt_me_writers_active_current 44
telemt_desync_total 620
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 7
telemt_pool_force_close_total 188
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 2378
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 172
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2240
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2190
telemt_me_writer_teardown_success_total{mode="normal"} 2412
telemt_me_writer_teardown_noop_total 2378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4790
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.506525
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4790
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 96863
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 1217410180 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 35451914424 (33.02 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 20302.4 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630529
telemt_connections_bad_total 29216
telemt_connections_current 424
telemt_connections_me_current 424
telemt_handshake_timeouts_total 23709
telemt_upstream_connect_attempt_total 8416
telemt_upstream_connect_success_total 8267
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 8401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 686
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 212
telemt_me_idle_close_by_peer_total 212
telemt_me_route_drop_no_conn_total 318877
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514060
telemt_me_endpoint_quarantine_total 170
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 42
telemt_desync_total 2284
telemt_desync_full_logged_total 1300
telemt_desync_suppressed_total 984
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 946
telemt_pool_swap_total 22
telemt_pool_force_close_total 626
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 7423
telemt_me_writer_removed_unexpected_total 201
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 644
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6978
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6797
telemt_me_writer_teardown_success_total{mode="normal"} 7622
telemt_me_writer_teardown_noop_total 7423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.239296
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 175
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 513355
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 8723330500 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 176004224252 (163.92 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 95162.3 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7321948
telemt_connections_bad_total 560517
telemt_connections_current 1798
telemt_connections_me_current 1798
telemt_handshake_timeouts_total 233789
telemt_upstream_connect_attempt_total 34342
telemt_upstream_connect_success_total 34273
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1465
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 4479342
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5991185
telemt_me_endpoint_quarantine_total 600
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 705
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 25431
telemt_desync_full_logged_total 8381
telemt_desync_suppressed_total 17050
telemt_desync_frames_bucket_total{bucket="1_2"} 5453
telemt_desync_frames_bucket_total{bucket="3_10"} 9940
telemt_desync_frames_bucket_total{bucket="gt_10"} 10038
telemt_pool_swap_total 102
telemt_pool_force_close_total 3450
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 560
telemt_me_draining_writers_reap_progress_total 31298
telemt_me_writer_removed_unexpected_total 700
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2663
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28912
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27848
telemt_me_writer_teardown_success_total{mode="normal"} 31575
telemt_me_writer_teardown_noop_total 31342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.342815
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 560
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5983830
telemt_user_connections_current{user="hello"} 1798
telemt_user_octets_from_client{user="hello"} 102720609840 (95.67 GB)
telemt_user_octets_to_client{user="hello"} 1948758027064 (1.77 TB)
telemt_user_unique_ips_current{user="hello"} 856
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 95163.7 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6020759
telemt_connections_bad_total 575985
telemt_connections_current 1693
telemt_connections_me_current 1693
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 197879
telemt_upstream_connect_attempt_total 38263
telemt_upstream_connect_success_total 37927
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 38103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1781
telemt_me_reconnect_success_total 747
telemt_me_reader_eof_total 723
telemt_me_idle_close_by_peer_total 723
telemt_me_route_drop_no_conn_total 2124853
telemt_me_route_drop_channel_closed_total 247
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4504722
telemt_me_endpoint_quarantine_total 580
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 727
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
telemt_desync_total 21663
telemt_desync_full_logged_total 7265
telemt_desync_suppressed_total 14398
telemt_desync_frames_bucket_total{bucket="1_2"} 5238
telemt_desync_frames_bucket_total{bucket="3_10"} 8392
telemt_desync_frames_bucket_total{bucket="gt_10"} 8033
telemt_pool_swap_total 104
telemt_pool_force_close_total 3141
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 342
telemt_me_draining_writers_reap_progress_total 29848
telemt_me_writer_removed_unexpected_total 699
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27929
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26707
telemt_me_writer_teardown_success_total{mode="normal"} 30480
telemt_me_writer_teardown_noop_total 29854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60334
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.820616
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60334
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 342
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4460168
telemt_user_connections_current{user="hello"} 1693
telemt_user_octets_from_client{user="hello"} 137129728809 (127.71 GB)
telemt_user_octets_to_client{user="hello"} 2081029168991 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 824
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 95127.6 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5944211
telemt_connections_bad_total 537381
telemt_connections_current 1626
telemt_connections_me_current 1626
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 188541
telemt_upstream_connect_attempt_total 44672
telemt_upstream_connect_success_total 44373
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 44508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1792
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 2083939
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4440953
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 709
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_active_current 44
telemt_desync_total 21562
telemt_desync_full_logged_total 7130
telemt_desync_suppressed_total 14432
telemt_desync_frames_bucket_total{bucket="1_2"} 5299
telemt_desync_frames_bucket_total{bucket="3_10"} 8216
telemt_desync_frames_bucket_total{bucket="gt_10"} 8047
telemt_pool_swap_total 102
telemt_pool_force_close_total 3021
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 31253
telemt_me_writer_removed_unexpected_total 723
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29349
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2806
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28232
telemt_me_writer_teardown_success_total{mode="normal"} 31982
telemt_me_writer_teardown_noop_total 31264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63246
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.127918
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63246
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 699
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4442487
telemt_user_connections_current{user="hello"} 1626
telemt_user_octets_from_client{user="hello"} 130250812459 (121.31 GB)
telemt_user_octets_to_client{user="hello"} 2034227932571 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 803
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 95167.3 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19788521
telemt_connections_bad_total 1417188
telemt_connections_current 2393
telemt_connections_me_current 2393
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 566536
telemt_upstream_connect_attempt_total 184407
telemt_upstream_connect_success_total 167057
telemt_upstream_connect_fail_total 15832
telemt_upstream_connect_attempts_per_request{bucket="1"} 182889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8862
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15832
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64068
telemt_me_reconnect_success_total 2055
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1302
telemt_me_route_drop_no_conn_total 39424665
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16157989
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 711
telemt_me_single_endpoint_outage_enter_total 113
telemt_me_single_endpoint_outage_exit_total 113
telemt_me_single_endpoint_outage_reconnect_attempt_total 241
telemt_me_single_endpoint_outage_reconnect_success_total 55
telemt_me_single_endpoint_quarantine_bypass_total 241
telemt_me_single_endpoint_shadow_rotate_total 739
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
telemt_me_writers_active_current 44
telemt_desync_total 31069
telemt_desync_full_logged_total 9214
telemt_desync_suppressed_total 21855
telemt_desync_frames_bucket_total{bucket="1_2"} 6794
telemt_desync_frames_bucket_total{bucket="3_10"} 13762
telemt_desync_frames_bucket_total{bucket="gt_10"} 10513
telemt_pool_swap_total 97
telemt_pool_force_close_total 3261
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 733
telemt_me_draining_writers_reap_progress_total 29497
telemt_me_writer_removed_unexpected_total 1920
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4020
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27130
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2745
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26236
telemt_me_writer_teardown_success_total{mode="normal"} 31150
telemt_me_writer_teardown_noop_total 29523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60673
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.190164
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60673
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 733
telemt_me_refill_failed_total 3783
telemt_me_writer_restored_same_endpoint_total 1441
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14670
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 16282678
telemt_user_connections_current{user="hello"} 2393
telemt_user_octets_from_client{user="hello"} 177795444146 (165.58 GB)
telemt_user_octets_to_client{user="hello"} 1079428160714 (1005.30 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1093
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 95134.4 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5750571
telemt_connections_bad_total 536138
telemt_connections_current 1809
telemt_connections_me_current 1809
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118616
telemt_upstream_connect_attempt_total 52565
telemt_upstream_connect_success_total 51960
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 52476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_reconnect_attempts_total 67900
telemt_me_reconnect_success_total 1569
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1334
telemt_me_route_drop_no_conn_total 2342884
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4484744
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 714
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 127
telemt_desync_total 22702
telemt_desync_full_logged_total 7906
telemt_desync_suppressed_total 14796
telemt_desync_frames_bucket_total{bucket="1_2"} 4315
telemt_desync_frames_bucket_total{bucket="3_10"} 8796
telemt_desync_frames_bucket_total{bucket="gt_10"} 9591
telemt_pool_swap_total 97
telemt_pool_force_close_total 2833
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32427
telemt_me_writer_removed_unexpected_total 1383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3407
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30423
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29594
telemt_me_writer_teardown_success_total{mode="normal"} 33830
telemt_me_writer_teardown_noop_total 32428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.678534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 4114
telemt_me_writer_restored_same_endpoint_total 1315
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 4477875
telemt_user_connections_current{user="hello"} 1809
telemt_user_octets_from_client{user="hello"} 120265180112 (112.01 GB)
telemt_user_octets_to_client{user="hello"} 1821537238798 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 903
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 31970.1 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3620297
telemt_connections_bad_total 127768
telemt_connections_current 1512
telemt_connections_me_current 1512
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1523020
telemt_upstream_connect_attempt_total 20579
telemt_upstream_connect_success_total 20447
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 20572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_reconnect_attempts_total 45480
telemt_me_reconnect_success_total 833
telemt_me_reader_eof_total 496
telemt_me_idle_close_by_peer_total 496
telemt_me_route_drop_no_conn_total 982255
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1734283
telemt_me_endpoint_quarantine_total 215
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 124
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9640
telemt_desync_full_logged_total 3257
telemt_desync_suppressed_total 6383
telemt_desync_frames_bucket_total{bucket="1_2"} 1708
telemt_desync_frames_bucket_total{bucket="3_10"} 3684
telemt_desync_frames_bucket_total{bucket="gt_10"} 4248
telemt_pool_swap_total 34
telemt_pool_force_close_total 1121
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 10147
telemt_me_writer_removed_unexpected_total 581
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1164
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9579
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 166
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9026
telemt_me_writer_teardown_success_total{mode="normal"} 10743
telemt_me_writer_teardown_noop_total 10148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20891
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.817211
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20891
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 2594
telemt_me_writer_restored_same_endpoint_total 745
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1738078
telemt_user_connections_current{user="hello"} 1512
telemt_user_octets_from_client{user="hello"} 51173498660 (47.66 GB)
telemt_user_octets_to_client{user="hello"} 744581474442 (693.45 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 642
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 12941.3 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143628
telemt_connections_bad_total 1360
telemt_connections_current 378
telemt_connections_me_current 378
telemt_handshake_timeouts_total 3479
telemt_upstream_connect_attempt_total 5797
telemt_upstream_connect_success_total 5780
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 125
telemt_me_reconnect_success_total 79
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 40395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124964
telemt_me_endpoint_quarantine_total 107
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 945
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 14
telemt_pool_force_close_total 341
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 5128
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 350
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4858
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 339
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4787
telemt_me_writer_teardown_success_total{mode="normal"} 5208
telemt_me_writer_teardown_noop_total 5128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10336
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.650448
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10336
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 124780
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 2316194312 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 76506393544 (71.25 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 95138.8 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6880745
telemt_connections_bad_total 698745
telemt_connections_current 1928
telemt_connections_me_current 1928
telemt_handshake_timeouts_total 195553
telemt_upstream_connect_attempt_total 36122
telemt_upstream_connect_success_total 35978
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 36085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 1466
telemt_me_reconnect_success_total 752
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 731
telemt_me_route_drop_no_conn_total 2079079
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5235826
telemt_me_endpoint_quarantine_total 635
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 728
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_active_current 44
telemt_desync_total 20121
telemt_desync_full_logged_total 6731
telemt_desync_suppressed_total 13390
telemt_desync_frames_bucket_total{bucket="1_2"} 4883
telemt_desync_frames_bucket_total{bucket="3_10"} 7325
telemt_desync_frames_bucket_total{bucket="gt_10"} 7913
telemt_pool_swap_total 105
telemt_pool_force_close_total 2877
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 32488
telemt_me_writer_removed_unexpected_total 708
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2634
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30575
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2789
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29611
telemt_me_writer_teardown_success_total{mode="normal"} 33209
telemt_me_writer_teardown_noop_total 32490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.472531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 673
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 5211174
telemt_user_connections_current{user="hello"} 1928
telemt_user_octets_from_client{user="hello"} 104746319768 (97.55 GB)
telemt_user_octets_to_client{user="hello"} 2449720905496 (2.23 TB)
telemt_user_unique_ips_current{user="hello"} 860
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 95135.3 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5893890
telemt_connections_bad_total 561196
telemt_connections_current 1791
telemt_connections_me_current 1791
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 165323
telemt_upstream_connect_attempt_total 52242
telemt_upstream_connect_success_total 51847
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 52183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_reconnect_attempts_total 5235
telemt_me_reconnect_success_total 1058
telemt_me_reader_eof_total 933
telemt_me_idle_close_by_peer_total 933
telemt_me_seq_mismatch_total 40
telemt_me_route_drop_no_conn_total 2131760
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4605481
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 723
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
telemt_desync_total 18877
telemt_desync_full_logged_total 6370
telemt_desync_suppressed_total 12507
telemt_desync_frames_bucket_total{bucket="1_2"} 4698
telemt_desync_frames_bucket_total{bucket="3_10"} 6874
telemt_desync_frames_bucket_total{bucket="gt_10"} 7305
telemt_pool_swap_total 103
telemt_pool_force_close_total 2832
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 31421
telemt_me_writer_removed_unexpected_total 945
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3115
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29294
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28589
telemt_me_writer_teardown_success_total{mode="normal"} 32409
telemt_me_writer_teardown_noop_total 31425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.561929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 51
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4608882
telemt_user_connections_current{user="hello"} 1791
telemt_user_octets_from_client{user="hello"} 87954522573 (81.91 GB)
telemt_user_octets_to_client{user="hello"} 1983727009040 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 814
telemt_user_unique_ips_recent_window{user="hello"} 181
```