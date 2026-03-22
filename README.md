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

# Server Metrics 2026-03-22 07:17:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 36638.3 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757440
telemt_connections_bad_total 47861
telemt_connections_current 1611
telemt_connections_me_current 1611
telemt_handshake_timeouts_total 35913
telemt_upstream_connect_attempt_total 14873
telemt_upstream_connect_success_total 14872
telemt_upstream_connect_attempts_per_request{bucket="1"} 14872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 232
telemt_me_reader_eof_total 229
telemt_me_idle_close_by_peer_total 229
telemt_me_route_drop_no_conn_total 296868
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627530
telemt_me_endpoint_quarantine_total 264
telemt_me_single_endpoint_shadow_rotate_total 300
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 5037
telemt_desync_full_logged_total 1418
telemt_desync_suppressed_total 3619
telemt_desync_frames_bucket_total{bucket="1_2"} 1626
telemt_desync_frames_bucket_total{bucket="3_10"} 1886
telemt_desync_frames_bucket_total{bucket="gt_10"} 1525
telemt_pool_swap_total 40
telemt_pool_force_close_total 1079
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 13484
telemt_me_writer_removed_unexpected_total 226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 930
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12766
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1064
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12405
telemt_me_writer_teardown_success_total{mode="normal"} 13696
telemt_me_writer_teardown_noop_total 13485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27181
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.777458
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27181
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 626341
telemt_user_connections_current{user="hello"} 1611
telemt_user_octets_from_client{user="hello"} 8617701328 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 214698724716 (199.95 GB)
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 50004.6 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1233000
telemt_connections_bad_total 120131
telemt_connections_current 1109
telemt_connections_me_current 1109
telemt_handshake_timeouts_total 38842
telemt_upstream_connect_attempt_total 26345
telemt_upstream_connect_success_total 25954
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 26293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1958
telemt_me_reconnect_success_total 788
telemt_me_reader_eof_total 686
telemt_me_idle_close_by_peer_total 686
telemt_me_route_drop_no_conn_total 467642
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 929158
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 401
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
telemt_me_writers_active_current 42
telemt_desync_total 4012
telemt_desync_full_logged_total 2344
telemt_desync_suppressed_total 1668
telemt_desync_frames_bucket_total{bucket="1_2"} 847
telemt_desync_frames_bucket_total{bucket="3_10"} 1547
telemt_desync_frames_bucket_total{bucket="gt_10"} 1618
telemt_pool_swap_total 53
telemt_pool_force_close_total 1420
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 20536
telemt_me_writer_removed_unexpected_total 659
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1831
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19350
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1352
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19116
telemt_me_writer_teardown_success_total{mode="normal"} 21181
telemt_me_writer_teardown_noop_total 20536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41717
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.331179
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41717
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 598
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 930904
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 14833602762 (13.81 GB)
telemt_user_octets_to_client{user="hello"} 341014281603 (317.59 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 723
telemt_user_unique_ips_recent_window{user="hello"} 416
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 124864.5 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8979883
telemt_connections_bad_total 826704
telemt_connections_current 4301
telemt_connections_me_current 4301
telemt_handshake_timeouts_total 280957
telemt_upstream_connect_attempt_total 46149
telemt_upstream_connect_success_total 46069
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1753
telemt_me_reconnect_success_total 915
telemt_me_reader_eof_total 918
telemt_me_idle_close_by_peer_total 918
telemt_me_route_drop_no_conn_total 4866746
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7077499
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 939
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 30676
telemt_desync_full_logged_total 10151
telemt_desync_suppressed_total 20525
telemt_desync_frames_bucket_total{bucket="1_2"} 6653
telemt_desync_frames_bucket_total{bucket="3_10"} 11919
telemt_desync_frames_bucket_total{bucket="gt_10"} 12104
telemt_pool_swap_total 135
telemt_pool_force_close_total 4457
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 42119
telemt_me_writer_removed_unexpected_total 882
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3499
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39002
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 269
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37662
telemt_me_writer_teardown_success_total{mode="normal"} 42501
telemt_me_writer_teardown_noop_total 42163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84664
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 177.312105
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84664
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 816
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 7068225
telemt_user_connections_current{user="hello"} 4301
telemt_user_octets_from_client{user="hello"} 119375349436 (111.18 GB)
telemt_user_octets_to_client{user="hello"} 2418625528540 (2.20 TB)
telemt_user_unique_ips_current{user="hello"} 1726
telemt_user_unique_ips_recent_window{user="hello"} 627
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 124866.0 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7401028
telemt_connections_bad_total 653130
telemt_connections_current 3921
telemt_connections_me_current 3921
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 243103
telemt_upstream_connect_attempt_total 50173
telemt_upstream_connect_success_total 49767
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2631
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 956
telemt_me_idle_close_by_peer_total 956
telemt_me_route_drop_no_conn_total 2488186
telemt_me_route_drop_channel_closed_total 303
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5487362
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 961
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
telemt_me_writers_active_current 45
telemt_desync_total 25223
telemt_desync_full_logged_total 8662
telemt_desync_suppressed_total 16561
telemt_desync_frames_bucket_total{bucket="1_2"} 6038
telemt_desync_frames_bucket_total{bucket="3_10"} 9771
telemt_desync_frames_bucket_total{bucket="gt_10"} 9414
telemt_pool_swap_total 136
telemt_pool_force_close_total 4060
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 40593
telemt_me_writer_removed_unexpected_total 933
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3369
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38086
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 236
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36533
telemt_me_writer_teardown_success_total{mode="normal"} 41455
telemt_me_writer_teardown_noop_total 40599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82054
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.967556
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82054
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 866
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5408382
telemt_user_connections_current{user="hello"} 3921
telemt_user_octets_from_client{user="hello"} 153816071305 (143.25 GB)
telemt_user_octets_to_client{user="hello"} 2615261514407 (2.38 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1642
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 124830.9 (34h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7168720
telemt_connections_bad_total 589814
telemt_connections_current 3205
telemt_connections_me_current 3205
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239146
telemt_upstream_connect_attempt_total 56711
telemt_upstream_connect_success_total 56051
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2697
telemt_me_reconnect_success_total 1167
telemt_me_reader_eof_total 1082
telemt_me_idle_close_by_peer_total 1082
telemt_me_route_drop_no_conn_total 2890491
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5350422
telemt_me_endpoint_quarantine_total 877
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 925
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
telemt_me_writers_active_current 78
telemt_desync_total 25003
telemt_desync_full_logged_total 8520
telemt_desync_suppressed_total 16483
telemt_desync_frames_bucket_total{bucket="1_2"} 6070
telemt_desync_frames_bucket_total{bucket="3_10"} 9582
telemt_desync_frames_bucket_total{bucket="gt_10"} 9351
telemt_pool_swap_total 133
telemt_pool_force_close_total 3895
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 41464
telemt_me_writer_removed_unexpected_total 1093
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3668
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38903
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37569
telemt_me_writer_teardown_success_total{mode="normal"} 42571
telemt_me_writer_teardown_noop_total 41476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84047
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.877056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84047
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1011
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 5344235
telemt_user_connections_current{user="hello"} 3205
telemt_user_octets_from_client{user="hello"} 142222969339 (132.46 GB)
telemt_user_octets_to_client{user="hello"} 2384614444815 (2.17 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1340
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 124869.2 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22906257
telemt_connections_bad_total 1916820
telemt_connections_current 5567
telemt_connections_me_current 5567
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 677961
telemt_upstream_connect_attempt_total 238905
telemt_upstream_connect_success_total 219270
telemt_upstream_connect_fail_total 17678
telemt_upstream_connect_attempts_per_request{bucket="1"} 236948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11035
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17678
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66409
telemt_me_reconnect_success_total 2632
telemt_me_reader_eof_total 1657
telemt_me_idle_close_by_peer_total 1655
telemt_me_route_drop_no_conn_total 43664097
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18449831
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 973
telemt_me_single_endpoint_outage_enter_total 156
telemt_me_single_endpoint_outage_exit_total 156
telemt_me_single_endpoint_outage_reconnect_attempt_total 325
telemt_me_single_endpoint_outage_reconnect_success_total 82
telemt_me_single_endpoint_quarantine_bypass_total 325
telemt_me_single_endpoint_shadow_rotate_total 976
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 35761
telemt_desync_full_logged_total 10694
telemt_desync_suppressed_total 25067
telemt_desync_frames_bucket_total{bucket="1_2"} 7924
telemt_desync_frames_bucket_total{bucket="3_10"} 15846
telemt_desync_frames_bucket_total{bucket="gt_10"} 11991
telemt_pool_swap_total 129
telemt_pool_force_close_total 4090
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 936
telemt_me_draining_writers_reap_progress_total 39030
telemt_me_writer_removed_unexpected_total 2435
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35924
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3507
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 583
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34940
telemt_me_writer_teardown_success_total{mode="normal"} 41196
telemt_me_writer_teardown_noop_total 39062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 280.411267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 936
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1792
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18614471
telemt_user_connections_current{user="hello"} 5567
telemt_user_octets_from_client{user="hello"} 271761004063 (253.10 GB)
telemt_user_octets_to_client{user="hello"} 1400588511642 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 2017
telemt_user_unique_ips_recent_window{user="hello"} 1144
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 124836.7 (34h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6840264
telemt_connections_bad_total 629983
telemt_connections_current 3775
telemt_connections_me_current 3775
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 141712
telemt_upstream_connect_attempt_total 65198
telemt_upstream_connect_success_total 64454
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 65092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_reconnect_attempts_total 70006
telemt_me_reconnect_success_total 1924
telemt_me_reader_eof_total 1701
telemt_me_idle_close_by_peer_total 1700
telemt_me_route_drop_no_conn_total 2627582
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5349916
telemt_me_endpoint_quarantine_total 833
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 947
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
telemt_me_writers_active_current 43
telemt_desync_total 26852
telemt_desync_full_logged_total 9352
telemt_desync_suppressed_total 17500
telemt_desync_frames_bucket_total{bucket="1_2"} 5380
telemt_desync_frames_bucket_total{bucket="3_10"} 10303
telemt_desync_frames_bucket_total{bucket="gt_10"} 11169
telemt_pool_swap_total 130
telemt_pool_force_close_total 3733
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 441
telemt_me_draining_writers_reap_progress_total 43739
telemt_me_writer_removed_unexpected_total 1732
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41126
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3318
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 415
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40006
telemt_me_writer_teardown_success_total{mode="normal"} 45508
telemt_me_writer_teardown_noop_total 43740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.033849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 441
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1608
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5341149
telemt_user_connections_current{user="hello"} 3775
telemt_user_octets_from_client{user="hello"} 136432933136 (127.06 GB)
telemt_user_octets_to_client{user="hello"} 2234846631658 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1561
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 61672.8 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5076345
telemt_connections_bad_total 205769
telemt_connections_current 3359
telemt_connections_me_current 3359
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2010993
telemt_upstream_connect_attempt_total 34084
telemt_upstream_connect_success_total 33851
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 34077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_reconnect_attempts_total 46214
telemt_me_reconnect_success_total 1074
telemt_me_reader_eof_total 765
telemt_me_idle_close_by_peer_total 765
telemt_me_route_drop_no_conn_total 1246357
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2530813
telemt_me_endpoint_quarantine_total 433
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 475
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 13474
telemt_desync_full_logged_total 4641
telemt_desync_suppressed_total 8833
telemt_desync_frames_bucket_total{bucket="1_2"} 2670
telemt_desync_frames_bucket_total{bucket="3_10"} 5151
telemt_desync_frames_bucket_total{bucket="gt_10"} 5653
telemt_pool_swap_total 67
telemt_pool_force_close_total 1969
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 22470
telemt_me_writer_removed_unexpected_total 835
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1892
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21435
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1744
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20501
telemt_me_writer_teardown_success_total{mode="normal"} 23327
telemt_me_writer_teardown_noop_total 22472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45799
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.963522
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45799
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 2622
telemt_me_writer_restored_same_endpoint_total 958
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2532502
telemt_user_connections_current{user="hello"} 3359
telemt_user_octets_from_client{user="hello"} 64772094664 (60.32 GB)
telemt_user_octets_to_client{user="hello"} 1124456822882 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1454
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 42643.5 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330310
telemt_connections_bad_total 2305
telemt_connections_current 678
telemt_connections_me_current 678
telemt_handshake_timeouts_total 7497
telemt_upstream_connect_attempt_total 20457
telemt_upstream_connect_success_total 20404
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 20453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 894
telemt_me_reconnect_success_total 299
telemt_me_reader_eof_total 295
telemt_me_idle_close_by_peer_total 295
telemt_me_route_drop_no_conn_total 99613
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299280
telemt_me_endpoint_quarantine_total 405
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 372
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 1453
telemt_desync_full_logged_total 407
telemt_desync_suppressed_total 1046
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 427
telemt_pool_swap_total 47
telemt_pool_force_close_total 1059
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 18507
telemt_me_writer_removed_unexpected_total 282
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1214
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17588
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17448
telemt_me_writer_teardown_success_total{mode="normal"} 18802
telemt_me_writer_teardown_noop_total 18507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37309
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.484898
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37309
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 298845
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 4884856972 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 169219952280 (157.60 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 124841.0 (34h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8361335
telemt_connections_bad_total 901708
telemt_connections_current 3978
telemt_connections_me_current 3978
telemt_handshake_timeouts_total 235164
telemt_upstream_connect_attempt_total 48960
telemt_upstream_connect_success_total 48780
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 48921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 1827
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 967
telemt_me_idle_close_by_peer_total 967
telemt_me_route_drop_no_conn_total 2346302
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6207824
telemt_me_endpoint_quarantine_total 889
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 954
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
telemt_me_writers_active_current 44
telemt_desync_total 24766
telemt_desync_full_logged_total 8128
telemt_desync_suppressed_total 16638
telemt_desync_frames_bucket_total{bucket="1_2"} 6139
telemt_desync_frames_bucket_total{bucket="3_10"} 9029
telemt_desync_frames_bucket_total{bucket="gt_10"} 9598
telemt_pool_swap_total 138
telemt_pool_force_close_total 3687
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 44188
telemt_me_writer_removed_unexpected_total 929
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3488
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41657
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40501
telemt_me_writer_teardown_success_total{mode="normal"} 45145
telemt_me_writer_teardown_noop_total 44190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89335
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.385366
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89335
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6181665
telemt_user_connections_current{user="hello"} 3978
telemt_user_octets_from_client{user="hello"} 122025055032 (113.64 GB)
telemt_user_octets_to_client{user="hello"} 2902499797528 (2.64 TB)
telemt_user_unique_ips_current{user="hello"} 1538
telemt_user_unique_ips_recent_window{user="hello"} 544
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 124838.6 (34h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7302000
telemt_connections_bad_total 780882
telemt_connections_current 4158
telemt_connections_me_current 4158
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 195006
telemt_upstream_connect_attempt_total 64843
telemt_upstream_connect_success_total 64350
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 64780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26237
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 621
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_reconnect_attempts_total 6015
telemt_me_reconnect_success_total 1383
telemt_me_reader_eof_total 1247
telemt_me_idle_close_by_peer_total 1247
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2414482
telemt_me_route_drop_channel_closed_total 199
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5556254
telemt_me_endpoint_quarantine_total 978
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 952
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 85
telemt_desync_total 23688
telemt_desync_full_logged_total 7877
telemt_desync_suppressed_total 15811
telemt_desync_frames_bucket_total{bucket="1_2"} 5866
telemt_desync_frames_bucket_total{bucket="3_10"} 8702
telemt_desync_frames_bucket_total{bucket="gt_10"} 9120
telemt_pool_swap_total 135
telemt_pool_force_close_total 3610
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 437
telemt_me_draining_writers_reap_progress_total 42682
telemt_me_writer_removed_unexpected_total 1262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4062
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39943
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39072
telemt_me_writer_teardown_success_total{mode="normal"} 44005
telemt_me_writer_teardown_noop_total 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86691
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.472670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86691
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 437
telemt_me_refill_failed_total 267
telemt_me_writer_restored_same_endpoint_total 1082
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5558097
telemt_user_connections_current{user="hello"} 4158
telemt_user_octets_from_client{user="hello"} 102792147705 (95.73 GB)
telemt_user_octets_to_client{user="hello"} 2416328980492 (2.20 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1751
telemt_user_unique_ips_recent_window{user="hello"} 488
```