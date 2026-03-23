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

# Server Metrics 2026-03-23 06:22:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 119741.0 (33h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4300620
telemt_connections_bad_total 408967
telemt_connections_current 1543
telemt_connections_me_current 1543
telemt_handshake_timeouts_total 146181
telemt_upstream_connect_attempt_total 44414
telemt_upstream_connect_success_total 44413
telemt_upstream_connect_attempts_per_request{bucket="1"} 44413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1554
telemt_me_reconnect_success_total 698
telemt_me_reader_eof_total 722
telemt_me_idle_close_by_peer_total 722
telemt_me_route_drop_no_conn_total 3567531
telemt_me_route_drop_channel_closed_total 1380
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3519262
telemt_me_writer_pick_total{mode="p2c",result="full"} 22
telemt_me_endpoint_quarantine_total 849
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 936
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 12
telemt_desync_total 14598
telemt_desync_full_logged_total 4624
telemt_desync_suppressed_total 9974
telemt_desync_frames_bucket_total{bucket="1_2"} 3775
telemt_desync_frames_bucket_total{bucket="3_10"} 5449
telemt_desync_frames_bucket_total{bucket="gt_10"} 5374
telemt_pool_swap_total 132
telemt_pool_force_close_total 4069
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 777
telemt_me_draining_writers_reap_progress_total 40688
telemt_me_writer_removed_unexpected_total 694
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38034
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36619
telemt_me_writer_teardown_success_total{mode="normal"} 40954
telemt_me_writer_teardown_noop_total 40701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81655
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 449.232033
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81655
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 777
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 626
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 3506470
telemt_user_connections_current{user="hello"} 1543
telemt_user_octets_from_client{user="hello"} 46363650688 (43.18 GB)
telemt_user_octets_to_client{user="hello"} 914582621084 (851.77 GB)
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 133106.6 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4209158
telemt_connections_bad_total 391991
telemt_connections_current 937
telemt_connections_me_current 937
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 111113
telemt_upstream_connect_attempt_total 82612
telemt_upstream_connect_success_total 81621
telemt_upstream_connect_fail_total 879
telemt_upstream_connect_attempts_per_request{bucket="1"} 82500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 879
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11088
telemt_me_reconnect_success_total 3980
telemt_me_reader_eof_total 3948
telemt_me_idle_close_by_peer_total 3947
telemt_me_route_drop_no_conn_total 3684918
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3337270
telemt_me_endpoint_quarantine_total 1084
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1047
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
telemt_me_writers_active_current 44
telemt_desync_total 13776
telemt_desync_full_logged_total 7774
telemt_desync_suppressed_total 6002
telemt_desync_frames_bucket_total{bucket="1_2"} 3123
telemt_desync_frames_bucket_total{bucket="3_10"} 5404
telemt_desync_frames_bucket_total{bucket="gt_10"} 5249
telemt_pool_swap_total 125
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 55871
telemt_me_writer_removed_unexpected_total 3869
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52771
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52379
telemt_me_writer_teardown_success_total{mode="normal"} 59784
telemt_me_writer_teardown_noop_total 55872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115656
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.022513
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115656
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 3520
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 3351611
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 45133321995 (42.03 GB)
telemt_user_octets_to_client{user="hello"} 849128716445 (790.81 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 207966.6 (57h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16803492
telemt_connections_bad_total 1707916
telemt_connections_current 2205
telemt_connections_me_current 2205
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 414638
telemt_upstream_connect_attempt_total 93222
telemt_upstream_connect_success_total 93111
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 93128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1735
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3279
telemt_me_reconnect_success_total 1704
telemt_me_reader_eof_total 1662
telemt_me_idle_close_by_peer_total 1659
telemt_me_route_drop_no_conn_total 14150292
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13345844
telemt_me_endpoint_quarantine_total 1412
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1574
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_me_writers_warm_current 27
telemt_desync_total 55962
telemt_desync_full_logged_total 17881
telemt_desync_suppressed_total 38081
telemt_desync_frames_bucket_total{bucket="1_2"} 12444
telemt_desync_frames_bucket_total{bucket="3_10"} 21914
telemt_desync_frames_bucket_total{bucket="gt_10"} 21604
telemt_pool_swap_total 225
telemt_pool_force_close_total 7200
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1114
telemt_me_draining_writers_reap_progress_total 71888
telemt_me_writer_removed_unexpected_total 1595
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66748
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6730
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64688
telemt_me_writer_teardown_success_total{mode="normal"} 72769
telemt_me_writer_teardown_noop_total 71942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.963053
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1114
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1475
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13345592
telemt_user_connections_current{user="hello"} 2205
telemt_user_octets_from_client{user="hello"} 201796426169 (187.94 GB)
telemt_user_octets_to_client{user="hello"} 3634831598035 (3.31 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 841
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 207967.8 (57h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12270055
telemt_connections_bad_total 1307987
telemt_connections_current 1328
telemt_connections_me_current 1328
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 355718
telemt_upstream_connect_attempt_total 107668
telemt_upstream_connect_success_total 106253
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 107154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4767
telemt_me_reconnect_success_total 2056
telemt_me_reader_eof_total 1911
telemt_me_idle_close_by_peer_total 1911
telemt_me_route_drop_no_conn_total 4631707
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9070331
telemt_me_endpoint_quarantine_total 1419
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1589
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_me_writers_warm_current 28
telemt_desync_total 39921
telemt_desync_full_logged_total 13501
telemt_desync_suppressed_total 26420
telemt_desync_frames_bucket_total{bucket="1_2"} 9903
telemt_desync_frames_bucket_total{bucket="3_10"} 15317
telemt_desync_frames_bucket_total{bucket="gt_10"} 14701
telemt_pool_swap_total 222
telemt_pool_force_close_total 6553
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 70029
telemt_me_writer_removed_unexpected_total 1941
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6133
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65700
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6038
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63476
telemt_me_writer_teardown_success_total{mode="normal"} 71833
telemt_me_writer_teardown_noop_total 70054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141887
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 105.108334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141887
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1752
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 9007828
telemt_user_connections_current{user="hello"} 1328
telemt_user_octets_from_client{user="hello"} 221041891564 (205.86 GB)
telemt_user_octets_to_client{user="hello"} 4052853002055 (3.69 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 207932.2 (57h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11408002
telemt_connections_bad_total 1050477
telemt_connections_current 1171
telemt_connections_me_current 1171
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 362102
telemt_upstream_connect_attempt_total 92045
telemt_upstream_connect_success_total 90464
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 90669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5933
telemt_me_reconnect_success_total 2516
telemt_me_reader_eof_total 2253
telemt_me_idle_close_by_peer_total 2252
telemt_me_route_drop_no_conn_total 5401543
telemt_me_route_drop_channel_closed_total 387
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8574986
telemt_me_endpoint_quarantine_total 1472
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1555
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_desync_total 39037
telemt_desync_full_logged_total 12978
telemt_desync_suppressed_total 26059
telemt_desync_frames_bucket_total{bucket="1_2"} 9841
telemt_desync_frames_bucket_total{bucket="3_10"} 14940
telemt_desync_frames_bucket_total{bucket="gt_10"} 14256
telemt_pool_swap_total 218
telemt_pool_force_close_total 6444
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 766
telemt_me_draining_writers_reap_progress_total 70635
telemt_me_writer_removed_unexpected_total 2398
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6878
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66092
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 577
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64191
telemt_me_writer_teardown_success_total{mode="normal"} 72970
telemt_me_writer_teardown_noop_total 70706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143676
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.322123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143676
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 766
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2185
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 8566716
telemt_user_connections_current{user="hello"} 1171
telemt_user_octets_from_client{user="hello"} 194831035295 (181.45 GB)
telemt_user_octets_to_client{user="hello"} 3555529540297 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 78211.8 (21h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11849496
telemt_connections_bad_total 720068
telemt_connections_current 2342
telemt_connections_me_current 2342
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 334364
telemt_upstream_connect_attempt_total 72465
telemt_upstream_connect_success_total 68716
telemt_upstream_connect_fail_total 2455
telemt_upstream_connect_attempts_per_request{bucket="1"} 71171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2455
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8586
telemt_me_reconnect_success_total 1597
telemt_me_reader_eof_total 1019
telemt_me_idle_close_by_peer_total 1018
telemt_me_route_drop_no_conn_total 25428335
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9775174
telemt_me_endpoint_quarantine_total 621
telemt_me_single_endpoint_outage_enter_total 112
telemt_me_single_endpoint_outage_exit_total 112
telemt_me_single_endpoint_outage_reconnect_attempt_total 214
telemt_me_single_endpoint_outage_reconnect_success_total 57
telemt_me_single_endpoint_quarantine_bypass_total 214
telemt_me_single_endpoint_shadow_rotate_total 626
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 17542
telemt_desync_full_logged_total 4930
telemt_desync_suppressed_total 12612
telemt_desync_frames_bucket_total{bucket="1_2"} 3395
telemt_desync_frames_bucket_total{bucket="3_10"} 7184
telemt_desync_frames_bucket_total{bucket="gt_10"} 6963
telemt_pool_swap_total 80
telemt_pool_force_close_total 2473
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 544
telemt_me_draining_writers_reap_progress_total 25921
telemt_me_writer_removed_unexpected_total 1473
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3344
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23996
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23448
telemt_me_writer_teardown_success_total{mode="normal"} 27340
telemt_me_writer_teardown_noop_total 25940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53280
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.382023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53280
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 544
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1020
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 9806355
telemt_user_connections_current{user="hello"} 2342
telemt_user_octets_from_client{user="hello"} 92115573964 (85.79 GB)
telemt_user_octets_to_client{user="hello"} 770190086708 (717.30 GB)
telemt_user_msgs_from_client{user="hello"} 78576
telemt_user_msgs_to_client{user="hello"} 74228
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 207938.3 (57h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11402282
telemt_connections_bad_total 1006216
telemt_connections_current 1693
telemt_connections_me_current 1693
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 259867
telemt_upstream_connect_attempt_total 121372
telemt_upstream_connect_success_total 120075
telemt_upstream_connect_fail_total 1118
telemt_upstream_connect_attempts_per_request{bucket="1"} 121193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1118
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73757
telemt_me_reconnect_success_total 3358
telemt_me_reader_eof_total 3034
telemt_me_idle_close_by_peer_total 3031
telemt_me_route_drop_no_conn_total 5351733
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8972318
telemt_me_endpoint_quarantine_total 1419
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1581
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_warm_current 7
telemt_desync_total 47669
telemt_desync_full_logged_total 16409
telemt_desync_suppressed_total 31260
telemt_desync_frames_bucket_total{bucket="1_2"} 9700
telemt_desync_frames_bucket_total{bucket="3_10"} 18268
telemt_desync_frames_bucket_total{bucket="gt_10"} 19701
telemt_pool_swap_total 213
telemt_pool_force_close_total 6123
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 74959
telemt_me_writer_removed_unexpected_total 3051
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7456
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 750
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68836
telemt_me_writer_teardown_success_total{mode="normal"} 78057
telemt_me_writer_teardown_noop_total 74960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.398000
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2826
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8974920
telemt_user_connections_current{user="hello"} 1693
telemt_user_octets_from_client{user="hello"} 200081644021 (186.34 GB)
telemt_user_octets_to_client{user="hello"} 3438719802244 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 678
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 144774.6 (40h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12211931
telemt_connections_bad_total 503085
telemt_connections_current 1183
telemt_connections_me_current 1183
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4916948
telemt_upstream_connect_attempt_total 70085
telemt_upstream_connect_success_total 69587
telemt_upstream_connect_fail_total 485
telemt_upstream_connect_attempts_per_request{bucket="1"} 70072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 485
telemt_me_reconnect_attempts_total 49453
telemt_me_reconnect_success_total 2006
telemt_me_reader_eof_total 1683
telemt_me_idle_close_by_peer_total 1682
telemt_me_route_drop_no_conn_total 4167076
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5868563
telemt_me_endpoint_quarantine_total 994
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1117
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 33056
telemt_desync_full_logged_total 11330
telemt_desync_suppressed_total 21726
telemt_desync_frames_bucket_total{bucket="1_2"} 6649
telemt_desync_frames_bucket_total{bucket="3_10"} 13013
telemt_desync_frames_bucket_total{bucket="gt_10"} 13394
telemt_pool_swap_total 154
telemt_pool_force_close_total 4334
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 399
telemt_me_draining_writers_reap_progress_total 54760
telemt_me_writer_removed_unexpected_total 1720
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4336
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52202
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3888
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 446
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50426
telemt_me_writer_teardown_success_total{mode="normal"} 56538
telemt_me_writer_teardown_noop_total 54767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111305
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.943984
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111305
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 399
telemt_me_refill_failed_total 2756
telemt_me_writer_restored_same_endpoint_total 1772
telemt_me_writer_restored_fallback_total 31
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4336
telemt_user_connections_total{user="hello"} 5860387
telemt_user_connections_current{user="hello"} 1183
telemt_user_octets_from_client{user="hello"} 122652435316 (114.23 GB)
telemt_user_octets_to_client{user="hello"} 2284756786722 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 125745.5 (34h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1793259
telemt_connections_bad_total 37727
telemt_connections_current 1056
telemt_connections_me_current 1056
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 39691
telemt_upstream_connect_attempt_total 58902
telemt_upstream_connect_success_total 58705
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 58863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 869
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 2559
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 1031
telemt_me_idle_close_by_peer_total 1031
telemt_me_route_drop_no_conn_total 678881
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1593575
telemt_me_endpoint_quarantine_total 1067
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1035
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 10668
telemt_desync_full_logged_total 3015
telemt_desync_suppressed_total 7653
telemt_desync_frames_bucket_total{bucket="1_2"} 3390
telemt_desync_frames_bucket_total{bucket="3_10"} 3993
telemt_desync_frames_bucket_total{bucket="gt_10"} 3285
telemt_pool_swap_total 136
telemt_pool_force_close_total 3443
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 50284
telemt_me_writer_removed_unexpected_total 993
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3792
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47533
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3355
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46841
telemt_me_writer_teardown_success_total{mode="normal"} 51325
telemt_me_writer_teardown_noop_total 50288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.743657
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1589089
telemt_user_connections_current{user="hello"} 1056
telemt_user_octets_from_client{user="hello"} 28286199685 (26.34 GB)
telemt_user_octets_to_client{user="hello"} 627324905371 (584.24 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 207943.0 (57h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13686762
telemt_connections_bad_total 1666811
telemt_connections_current 1622
telemt_connections_me_current 1622
telemt_handshake_timeouts_total 401106
telemt_upstream_connect_attempt_total 83936
telemt_upstream_connect_success_total 83567
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 83799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3304
telemt_me_reconnect_success_total 1651
telemt_me_reader_eof_total 1642
telemt_me_idle_close_by_peer_total 1642
telemt_me_route_drop_no_conn_total 4553795
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10315271
telemt_me_endpoint_quarantine_total 1539
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1580
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_warm_current 11
telemt_desync_total 43458
telemt_desync_full_logged_total 14144
telemt_desync_suppressed_total 29314
telemt_desync_frames_bucket_total{bucket="1_2"} 10558
telemt_desync_frames_bucket_total{bucket="3_10"} 15989
telemt_desync_frames_bucket_total{bucket="gt_10"} 16911
telemt_pool_swap_total 230
telemt_pool_force_close_total 5993
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 709
telemt_me_draining_writers_reap_progress_total 75974
telemt_me_writer_removed_unexpected_total 1570
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5827
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5819
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69981
telemt_me_writer_teardown_success_total{mode="normal"} 77606
telemt_me_writer_teardown_noop_total 75976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153582
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.153119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153582
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 709
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10281582
telemt_user_connections_current{user="hello"} 1622
telemt_user_octets_from_client{user="hello"} 197848357764 (184.26 GB)
telemt_user_octets_to_client{user="hello"} 4587681365656 (4.17 TB)
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 207939.4 (57h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11997379
telemt_connections_bad_total 1411144
telemt_connections_current 1552
telemt_connections_me_current 1552
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 322626
telemt_upstream_connect_attempt_total 111963
telemt_upstream_connect_success_total 111003
telemt_upstream_connect_fail_total 750
telemt_upstream_connect_attempts_per_request{bucket="1"} 111753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 750
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11181
telemt_me_reconnect_success_total 2801
telemt_me_reader_eof_total 2596
telemt_me_idle_close_by_peer_total 2595
telemt_me_seq_mismatch_total 113
telemt_me_route_drop_no_conn_total 5723706
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9235427
telemt_me_endpoint_quarantine_total 1724
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1582
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_me_writers_active_current 52
telemt_me_writers_warm_current 7
telemt_desync_total 43366
telemt_desync_full_logged_total 13858
telemt_desync_suppressed_total 29508
telemt_desync_frames_bucket_total{bucket="1_2"} 11246
telemt_desync_frames_bucket_total{bucket="3_10"} 16026
telemt_desync_frames_bucket_total{bucket="gt_10"} 16094
telemt_pool_swap_total 220
telemt_pool_force_close_total 5734
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 76473
telemt_me_writer_removed_unexpected_total 2631
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71966
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70739
telemt_me_writer_teardown_success_total{mode="normal"} 79211
telemt_me_writer_teardown_noop_total 76478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 152945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 154766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 155320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 155639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 155689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 155689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 155689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 155689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 155689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 155689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 155689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 155689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 155689
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.873232
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 155689
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 435
telemt_me_writer_restored_same_endpoint_total 2231
telemt_me_writer_restored_fallback_total 148
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 9239680
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 160475340340 (149.45 GB)
telemt_user_octets_to_client{user="hello"} 3616643836042 (3.29 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 202
```